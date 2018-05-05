## Changes

* Added `UserLogin` resource;
    * Removed parser in each resource, instead making it global to the file and private.
    * Added `safe_str_cmp` and password checking in the resource.
    * Imported and added it in `app.py`
    * Mention `app.config['JWT_SECRET_KEY']` in `app.py` as well
* Removed `security.py` file
* Modified `item.py` since it was using `flask_jwt`
    * Changed `@jwt_required()` to `@jwt_required`
* Added `requirements.txt`
## Changes

* Added `UserLogout` resource in `user.py`;
    * Imported and added to `app.py`
* Modified blacklist loader so it checks the JWT's `'jti'` key instead of the `'identity'`.
* Made `BLACKLIST` initially an empty set.
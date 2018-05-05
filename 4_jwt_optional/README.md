## Changes

* Added `@jwt_optional` to `ItemList.get()`. If user is logged in, return full item info. Otherwise, only return item names.
* Can use `get_jwt_identity()` to retrieve the identity saved in the JWT when it was created.
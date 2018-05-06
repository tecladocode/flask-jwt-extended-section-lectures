## Changes

* Added `@fresh_jwt_required` to `Item.post()`. This means that the JWT provided must be fresh (generated with username/password) instead of having been refreshed.
    * Many places do this e.g. if you want to delete your account or something important.

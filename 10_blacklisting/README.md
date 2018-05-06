## Changes

* Added new `blacklist.py` file, with a single set of blacklisted user identities.
    * Imported in `app.py`;
    * Added new `@jwt.token_in_blacklist_loader` as well.
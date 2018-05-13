## Changes

* Added new `blacklist.py` file, with a single set of blacklisted user identities.
    * Imported in `app.py`;
    * Added new `@jwt.token_in_blacklist_loader` as well.
    * Added `app.config['JWT_BLACKLIST_ENABLED'] = True  # enable blacklist feature`
    * Added `app.config['JWT_BLACKLIST_TOKEN_CHECKS'] = ['access', 'refresh']  # allow blacklisting for access and refresh tokens`
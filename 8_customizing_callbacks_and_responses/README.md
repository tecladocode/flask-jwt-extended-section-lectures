## Changes

* Added configuration to `app.py` on JWT.
    * `@jwt.expired_token_loader`, for when the provided access token is valid but expired.
    * `@jwt.invalid_token_loader`, for when the provided token is invalid.
    * `@jwt.unauthorized_loader`, for when a token isn't present.
    * `@jwt.needs_fresh_token_loader`, for when the request needs a fresh token but it had a non-fresh token.
    * `@jwt.revoked_token_loader`, for when a token has been revoked.
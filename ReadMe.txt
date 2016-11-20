Requirements:

    * openssl
    * base32 (from GNU coreutils)

You are recommended to use it with "pass" from http://www.passwordstore.org/

For example, to get the token for two-factor authentication:

    totp GitHub "$(pass show otp/GitHub)"

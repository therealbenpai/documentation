## Commands

### Token

> [!tldr]- Command Description
> JSON Web Token (JWT) Utilities [^1]

#### <u>Generate</u>

> [!tldr]- Description
> Generates a JSON Web Token (JWT)[^1]

> [!success]
> Upon success, the command should output the JWT string as well as the incorporated UID for the `sub` claim[^2]

> [!failure]
> Upon failure, the error should be outputted to the console to allow for the section of code to be fixed

>[!bug] Known Bugs
> - For some reason, validation using [jwt.io](https://jwt.io) fails

##### Options

#### <u>Verify</u>

> [!tldr]- Description
> Verifies a JSON Web Token (JWT)[^1]

> [!success]

> [!failure]

##### Options

#### <u>Deserialize</u>

> [!tldr]- Description
> Decodes/Deserializes a JSON Web Token (JWT)[^1]

> [!success]

> [!failure]

##### Options

### Password

> [!tldr]- Command Description
> Password Utilities

#### <u>Hash</u>

> [!tldr]- Description
> Hashes a password using the Argon2id[^3] format

> [!success]

> [!failure]

##### Options

#### <u>Verify</u>

> [!tldr]- Description
> Verifies a password using the hash and the plaintext password input

> [!success]

> [!failure]

##### Options

## Global Options

## Footnotes

[^1]: JSON Web Token is defined in [RFC 7519](https://datatracker.ietf.org/doc/html/rfc7519)

[^2]: JWT Claims can be found on the IANA's website at the following link: [here](https://www.iana.org/assignments/jwt/jwt.xhtml)

[^3]: Argon2 is defined on [RFC 9106](https://datatracker.ietf.org/doc/rfc9106/)
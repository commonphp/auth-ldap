# CommonPHP LDAP Auth Driver

Authentication driver for CommonPHP that uses LDAP as an authentication source.

## Requirements

- PHP `^8.5`
- `comphp/auth:^0.3`
- LDAP support through the applicable PHP extension or LDAP integration library

## Installation

Once this package is available through your Composer repositories, install it with:

```bash
composer require comphp/auth-ldap
```

## Usage

```php
<?php

// TODO: Write usage
```

## Driver Notes

This driver is intended for applications that authenticate users against an LDAP directory such as Active Directory or another LDAP-compatible identity source.

The driver should handle LDAP-specific connection, bind, search, and credential verification behavior while exposing the common auth driver contract used by CommonPHP.

## Error Handling

LDAP connection failures, bind failures, lookup failures, invalid configuration, and authentication source errors should throw CommonPHP auth driver exceptions instead of returning ambiguous false values.

## Documentation

- [Usage](docs/usage.md)
- [Testing](TESTING.md)
- [Contributing](CONTRIBUTING.md)
- [Security](SECURITY.md)

## License

MIT. See [LICENSE.md](LICENSE.md).

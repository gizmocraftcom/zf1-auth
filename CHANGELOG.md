# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-auth`, published as `gizmocraft/zendframework1-auth`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-auth` to `gizmocraft/zendframework1-auth`. It now requires `gizmocraft/zendframework1-exception` `^2.0.0` and `gizmocraft/zendframework1-session` `^3.0.0`.
- Dropped the `suggest` entry for `zendframework1-auth-adapter-openid`: the OpenId adapter is not part of the gizmocraft forks because it depends on the excluded `Zend_OpenId` package.

### Other changes

- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes.
- CI runs PHP 8.5 and 8.6.

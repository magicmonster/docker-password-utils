# Password utils

## Dovecot
To hash your password run
```
docker run -it --rm magicmonster/password-utils doveadm pw
```
The output can be used by dovecot as a password field

## References
1. Dovecot [Passwd-file](https://doc.dovecot.org/configuration_manual/authentication/passwd_file/#authentication-passwd-file)



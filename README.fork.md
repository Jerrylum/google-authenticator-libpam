### Add option `no_drop_privileges`


By default the PAM module will try to become the new user before opening the
secrets file.

This option can be used to allow daemons not to drop privileges.

# Librum

I have not yet managed to get this to work, even with default settings.

Currently bumping in to an access denied error. `[Warning] Access denied for user 'librum'@'172.29.0.3' (using password: YES)`

With the provided `docker-compose.yml` and `.env` this is resolved, but I encounter the error `Access to the path '/var/lib/librum-server/librum_storage/books' is denied`.

This can be resolved by following the steps [here](https://github.com/Librum-Reader/Librum-Server/issues/20), but upon trying to log in to the local client we are presented with the error `We're sorry. Logging you in failed, please try again later.`

## Librum reader

Config files can be found at `.var/app/com.librumreader.librum/config/Librum-Reader/Librum.conf`. Default settings and more can be found [here](.var/app/com.librumreader.librum/config/Librum-Reader/Librum.conf).
# vaultwarde-config

This my [vaultwarden](https://github.com/dani-garcia/vaultwarden/) config as it 
runs on my raspbery pi. This is published via traefik (see my 
[traefik-config](https://github.com/StefanSchoof/traefik-config)). This is in the 
sense of Linus Torvalds "Real men don’t use backups, they post their stuff on a 
public ftp server and let the rest of the world make copies."

If this helps someone else, this is of course great.

## .env

```
ADMIN_TOKEN=<ADMIN-Token>
HOST=<traefik host>
```
For admin Token see 
https://github.com/dani-garcia/vaultwarden/wiki/Enabling-admin-page

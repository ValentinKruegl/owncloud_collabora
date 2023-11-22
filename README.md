The image sets up 3 websites:
   - a traefik dashboard
   - a owncloud
   - a collabora server

If wanted, the traefik dashboard can be disabled by commenting out most of the labels. The compose works with a .env file, below is a example version

To start the server:
clone this repository locally and cd into the toplevel directory
run `docker compose up -d` (or `docker-compose up -d` depending on docker version)


If you want to change collabora app config, edit the 01-collabora.sh script and add commands according to the documentation:
https://doc.owncloud.com/server/next/admin_manual/configuration/server/occ_command.html#collabora-online-secure-view

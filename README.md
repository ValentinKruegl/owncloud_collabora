The image sets up 3 websites:
   - a traefik dashboard (can be disabled)
   - a owncloud
   - a collabora server

If wanted, the traefik dashboard can be disabled by commenting out most of the labels. 

To start the server:
 1. clone this repository locally 
 2. cd into the toplevel directory
 3. run `docker compose up -d` (or `docker-compose up -d` depending on docker version)


If you want to configure the owncloud collabora app on startup, edit the 01-collabora.sh script and add commands according to the documentation:
https://doc.owncloud.com/server/next/admin_manual/configuration/server/occ_command.html#collabora-online-secure-view

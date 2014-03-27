nginx config
============

The custom.conf file goes into (for Ubuntu) /etc/nginx/conf.d/. This allows for nginx to be upgraded without having to worry about default setup config files.

You should also delete the symlink /etc/nginx/sites-enabled/default if you plan on using a different default server config, e.g, the one in vhost/default.

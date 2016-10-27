# nginx-wordpress
Basic Nginx conf with SSL certificate and various optimizations for a Wordpress website.

## `.conf` files

* [cache.conf](cache.conf): basic caching instructions
* [gzip.conf](gzip.conf): gzipping instructions for static assets
* [myfastcgi.conf](myfastcgi.conf): PHP processing
* [nginx.conf](nginx.conf): main file of our configuration
* [rules.conf](rules.conf): various conditional rules
* [whitelist.conf](whitelist.conf): IP addresses that are trusted
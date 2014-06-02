dokku-path-proxy
================

Dokku path based routing to cointainers from the default_server nginx.

This plugin installs the nginx.conf as the /etc/nginx/sites-available/default configuration on the host machine.

After an app is deployed a new 
    ```
    location /$APP {
    }
    ```
is added routing this location to the deployed container.

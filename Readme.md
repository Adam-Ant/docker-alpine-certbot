# Alpine Certbot

A very simple dockerfile used for auto or manual certbot renewal.


## Example:

``` docker run --rm -v /voluimes/Lets-Encrypt:/etc/letsencrypt adamant/alpine-certbot renew --agree-tos ```

Note no need to call the certbot executable, as its provided in the entrypoint. This command could be placed in a crontab to automate this process.

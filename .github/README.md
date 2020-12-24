# Docker Compose Let's Encrypt / Nginx-proxy Companion

adapted from:
https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion

## Notes

A change has been made to the `test_start_ssl.sh` script to use 2048 sized RSA keys when requesting a certificate. This is for later uploading and usage with AWS ACM which can only use 2048 or smaller when integrating with other services (though 4096 can be uploaded they can't be used with services like CloudFront)

# Docker Compose Let's Encrypt / Nginx-proxy Companion

adapted from:
https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion

## Notes

A change has been made to the `test_start_ssl.sh` script to use 2048 sized RSA keys when requesting a certificate. This is for later uploading and usage with AWS ACM which can only use 2048 or smaller when integrating with other services (though 4096 can be uploaded they can't be used with services like CloudFront)

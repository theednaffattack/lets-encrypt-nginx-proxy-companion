# How to Revoke a Lets Encrypt Certification

```bash
certbot -c ~/.config/certbot/cli.ini revoke --cert-path ./cert.pem --reason keycompromise --key-path ./key.pem
```

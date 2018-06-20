# haproxy

1. Install certbot
2. Install cloudflare plugins
3. Wildcard and ACMEv2 server
4. Check new obtained certificates
5. Autorenew certificates


DOMAIN='yourdomain.com' sudo -E bash -c 'cat /etc/letsencrypt/live/$DOMAIN/fullchain.pem /etc/letsencrypt/live/$DOMAIN/privkey.pem > /etc/haproxy/ssl/$DOMAIN.pem'


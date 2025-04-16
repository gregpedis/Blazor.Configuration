# Blazor.Configuration

Configuration files for deploying Blazor WASM in a VPS with NGINX.

## How-to

- copy `ui/homepage.html` (automated)
- copy `ui/gregpaidis.css` (automated)
- copy `.bashrc`

- copy `nginx/nginx.conf`
- copy `nginx/gregpaidis`
- run `ln -s /etc/nginx/sites-available/gregpaidis /etc/nginx/sites-enabled/`
- run `nginx -t`
- run `systemctl restart nginx`

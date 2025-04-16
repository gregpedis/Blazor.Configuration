# Blazor.Configuration

Configuration files for deployment Blazor WASM in a VPS with NGINX.

## How-to

- copy `.bashrc`
- copy `homepage.html`
- copy `nginx.conf`
- copy `gregpaidis`
- run `ln -s /etc/nginx/sites-available/gregpaidis /etc/nginx/sites-enabled/`
- run `nginx -t`
- run `systemctl restart nginx`

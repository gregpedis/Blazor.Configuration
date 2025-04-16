# Blazor.Configuration

Configuration files for deploying Blazor WASM in a VPS with NGINX.

## How-to

- copy `.bashrc` 
- copy `homepage/`
- copy `nginx/nginx.conf`
- copy `nginx/gregpaidis`
- run `ln -s /etc/nginx/sites-available/gregpaidis /etc/nginx/sites-enabled/ || echo "Symbolic link already exists. Skipping..."`
- run `nginx -t && systemctl restart nginx`

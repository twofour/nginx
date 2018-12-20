# twofour/nginx

## Usage

    docker run -it --rm -p 80:80 -v $PWD:/var/www/html/htdocs twofour/nginx

## Environment variables

### NGINX_RESOLVERS

Default: 8.8.8.8 8.8.4.4 1.1.1.1 1.0.0.1

### NGINX_RESOLVER_VALID

Default: 300s

### NGINX_RESOLVER_TIMEOUT

Default: 60s

### NGINX_CLIENT_BODY_SIZE_MAX

Default: 32m

### NGINX_PROXY_READ_TIMEOUT

Default: 30s

### NGINX_PROXY_SEND_TIMEOUT

Default: 30s

### NGINX_SEND_TIMEOUT

Default: 30s

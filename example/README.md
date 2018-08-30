## Docker image base on Ubuntu with PHP v.7.1 + composer + cron with open port 80,443 and docker-compose exemple

### if we don`t have certificates, create the SSL key and certificate files in one motion by typing:
```
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/nginx.key -out /etc/nginx/ssl/nginx.crt
```

### The entirety of the prompts will look something like this:
```
Country Name (2 letter code) [AU]:US 
State or Province Name (full name) [Some-State]:New York
Locality Name (eg, city) []:New York City
Organization Name (eg, company) [Internet Widgits Pty Ltd]:Bouncy Castles, Inc.
Organizational Unit Name (eg, section) []:Ministry of Water Slides
Common Name (e.g. server FQDN or YOUR name) []:your_domain.com /* MOST IMPORTANT */
Email Address []:admin@your_domain.com
```

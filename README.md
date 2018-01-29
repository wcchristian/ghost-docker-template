# personal-site
New version of my personal site.

In the past I was using a bootstrap template for the main page and then from there you could navigate to the ghost blog. 
From now on I want to simplify things a bit and only use a ghost site. I plan to modify the stock ghost theme to handle a custom home page.

IN DEVELOPMENT: More info to follow.


docker run -p 443:443 -p 83:80 -v "./certs:/etc/letsencrypt" -v "./certs-lib:/var/lib/letsencrypt" certbot/certbot certonly

https://medium.com/@pierangelo1982/docker-nginx-and-letsencrypt-432397db4a0c
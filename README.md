# hypha-tokensale-satic-website

using docker:

from inside the website folder run the command:

docker run -d -p 8080:80 --name hypha-tokensale -v "$PWD":/var/www/html php:apache /bin/bash -c 'a2enmod rewrite; apache2-foreground'

then visit
https://localhost:8080 

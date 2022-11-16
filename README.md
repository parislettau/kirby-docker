# getKirbyDocker
dockerfile for getkirby starterkit, php:7.4-apache, composer
https://getkirby.com/

How to use it?
1) Install Docker
2) Get the Image

    a)Build an image from this Dockerfile:
    In the Folder where the Dockerfile is run
    
    docker build -t mykirby_image:1.0 .

    b)Alternatively, you can:
    Download image: 
    
    docker pull severinlx/getkirby

3) Start a container from this image on port 80

4) Call http://localhost/ in Browser and enjoy the Website


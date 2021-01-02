
> docker build -t nasa-picture .  

> docker images

> docker run -p 3333:8080 nasa-picture

> docker container ls -a


 > docker login --username=[username]

 > docker tag [imageId] [username]/nasa-picture:firsttry

 > docker push [username]/nasa-picture

 > docker pull [username]/nasa-picture:firsttry
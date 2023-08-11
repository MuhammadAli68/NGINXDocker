# NGINXDocker
Includes Dockerfile for NGINX conatiner

# Observations
Used "docker build -t my-nginx-image ." to build image for docker file then ran command "docker run -v my_volume:/usr/share/nginx/html -p 8080:8080 my-nginx-image" to build container
and attach my_volume to path /usr/share/nginx/html</br>
Default page at http://localhost:8080 is accesible in browser but not in postman</br>
if container created through "docker run -v my_volume:/usr/share/nginx/html -p 8080:80 my-nginx-image" then default page of nginx becomes accessible on postman as well

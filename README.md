# NGINXDocker
Includes Dockerfile for NGINX conatiner

# Observations
+ Used "docker build -t my-nginx-image ." to build image for docker file then ran command "docker run -v my_volume:/usr/share/nginx/html -p 8080:80 my-nginx-image" to build container
and attach my_volume to path /usr/share/nginx/html</br>
+Default page at http://localhost:8080 is accesible in browser and in postman</br>
__LOGS__
![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/1f43e6f9-c171-4cc1-9010-ecf9e2daf1dd)
__Browser__
![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/ae49cb3d-26fa-4b89-8ed1-42390c9200ae)
__Postman__
![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/4662a20d-4c66-4290-982e-0c05e4fcc614)
+ copied index.html using command "docker cp C:\Users\M.Ali\Desktop\index.html exciting_tu:/usr/share/nginx/html"
  __Output__
  ![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/6e9296c1-3896-4d17-95af-e30f3bb4f873)
+ index.html file becomes accessible over http://localhost:8080
__Browser__
![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/555a256f-2532-47d7-bcfe-1255698d1f5d)
__Postman__
![image](https://github.com/MuhammadAli68/NGINXDocker/assets/57432644/433f0241-fe09-49dd-9c31-fc5d119b1302)





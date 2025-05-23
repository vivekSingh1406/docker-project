# docker-project
                              
 
# All Command

you might want to see all the images
```
docker images 
```  

```
docker rmi $(docker images -q)
```  

You can delete all Docker images
```
docker images 
```  
If some images are being used by running containers, you may need to stop and remove those containers firs
```
docker rmi -f $(docker images -q)
```  
Lists running containers.
```
docker ps 
```  

Lists running containers.
```
docker container prune
```  

Lists running containers.
```
docker ps 
```  

command will prompt you for confirmation and remove all stopped containers
```
docker ps 
```  

vivek_react is a image name
```

docker build -t vivek_react . 
```  
run image file in port num 8000
first is - 8000 using localhost
second is- 8000 docker file
```
docker run -d -p 8000:8000 vivek_react 
```  

vivek_react - is a image name
tagname - give the tagname show in repo
```
docker tag vivek_react vivek1406/singh_vivek:tagname   
```  

vivek1406/singh_vivek: - your repo name
tagname - give the tagname show in repo
```
docker push vivek1406/singh_vivek:tagname
```  


## How to Build
```
docker build -t hello-world-java-docker .
```  
```bash
docker build -t spring-boot-rest-api .
```

## How to Run
```
docker run -it hello-world-java-docker
```

Run the Docker container using the command shown below.

```bash
docker run -d -p 8080:8080 spring-boot-rest-api
```

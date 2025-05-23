# docker-project


# All Command

- docker images   // you might want to see all the images
- docker rmi $(docker images -q)  // You can delete all Docker images
- docker rmi -f $(docker images -q)  // If some images are being used by running containers, you may need to stop and remove those containers firs

- docker ps   // Lists running containers.
- docker container prune   // command will prompt you for confirmation and remove all stopped containers

- docker build -t vivek_react .   // vivek_react is a image name
- docker run -d -p 8000:8000 vivek_react    // run image file in port num 8000
- docker tag vivek_react vivek1406/singh_vivek:tagname   // vivek_react - is a image name
                                                         // tagname - give the tagname show in repo
- docker push vivek1406/singh_vivek:tagname  // vivek1406/singh_vivek: - your repo name
                                             // tagname - give the tagname show in repo
                                             
                                             
                                             
 
# All Command

- docker images   // you might want to see all the images
- docker rmi $(docker images -q)  // You can delete all Docker images
- docker rmi -f $(docker images -q)  // If some images are being used by running containers, you may need to stop and remove those containers firs

- docker ps   // Lists running containers.
- docker container prune   // command will prompt you for confirmation and remove all stopped containers

- docker build -t vivek_react .   // vivek_react is a image name
- docker run -d -p 8000:8000 vivek_react    // run image file in port num 8000
- docker tag vivek_react vivek1406/singh_vivek:tagname   // vivek_react - is a image name
                                                         // tagname - give the tagname show in repo
- docker push vivek1406/singh_vivek:tagname  // vivek1406/singh_vivek: - your repo name
                                             // tagname - give the tagname show in repo





## How to Build
```
docker build -t hello-world-java-docker .
```  

## How to Run
```
docker run -it hello-world-java-docker
```


```bash
docker build -t spring-boot-rest-api .
```
Run the Docker container using the command shown below.

```bash
docker run -d -p 8080:8080 spring-boot-rest-api
```

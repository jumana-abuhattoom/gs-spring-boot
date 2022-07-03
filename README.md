# gs-spring-boot

*  https://github.com/spring-guides/gs-spring-boot.git 

## Build and Push Container

```sh
git clone https://github.com/jumana-abuhattoom/gs-spring-boot.git
cd gs-spring-boot
docker build -t gs-spring-boot .
docker tag gs-spring-boot jumanaah/gs-boot:latest
docker push jumanaah/gs-spring-boot:latest
```

![docker](https://user-images.githubusercontent.com/57894655/177056817-e33cac10-c701-4104-8bc2-9d1256c3fa2a.PNG)


## Run Container

To run the container, you can use the following commands:

```sh
git clone https://github.com/jumana-abuhattoom/gs-spring-boot.git
cd gs-spring-boot
docker build -t gs-spring-boot .
docker run -d -p 8080:8080 gs-boot
```
**  Visit the application at http://localhost:8080/ and check if with every time you visit the localhost:8080 the number shown in text increases with 1. 
 

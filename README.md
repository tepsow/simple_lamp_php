# simple_lamp_php
Lab 8  lampp: PHP:7.4.3 (backend) + Apache(backend+frontend) + MySQL (backend) 


***#Clone repository:***
```
git clone  https://github.com/tepsow/simple_lamp_php.git
cd simple_lamp_php
```
***#Run***
```
docker-compose up -d
```
***#Check:***
```
http://localhost:6789/
```
***#Grafical representation (from project folder)***
```
docker container run --rm -it --name dcv --mount type=bind,source="$(pwd)",destination=/input pmsipilot/docker-compose-viz
```
**Grafical reresentation png**
![Grafical reresentation png](https://github.com/tepsow/simple_lamp_php/blob/main/docker-compose.png)

#More about grafical representation
https://github.com/pmsipilot/docker-compose-viz

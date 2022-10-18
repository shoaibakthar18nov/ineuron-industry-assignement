1 docker --version

![docker version](https://user-images.githubusercontent.com/114742949/196515727-203d9c6f-f944-4ab7-9374-0fe693b49d05.png)

this command to ccheck the version of the docker

2 docker pull docker/getting-started 

![docker pull docker desktop](https://user-images.githubusercontent.com/114742949/196519968-d4a89dc3-beff-4b21-93d2-3ea2f957c611.png)

it means downloading images from docker/getting-started to ou local repositary

3 docker images

![docker images](https://user-images.githubusercontent.com/114742949/196522635-e0d444b2-2715-4bc9-8aa7-9271b3bf3882.png)

to check the all the images are present in the docker 

4 docker run -d -p 80:80 docker/getting-started

![docker run](https://user-images.githubusercontent.com/114742949/196523220-bab506f8-0775-4eef-8789-4bb014bfa451.png)

this command is used to run which means -d gives the detache mode runs the backend will run and -p means assigning the port i,e 80:80 host port number and other is container port number

5 docker ps

![docker ps](https://user-images.githubusercontent.com/114742949/196524716-0dd79b75-28d9-475e-96c8-2f3837abdaf6.png)

this command give which docker image is running

so below scrren short shows the image of docker/getting-started

![docker loacal host 80](https://user-images.githubusercontent.com/114742949/196525720-4bb2f051-4e77-4657-abc0-9b62af2a1fbe.png)

6 docker build -t welcome-app .

![docker build](https://user-images.githubusercontent.com/114742949/196526410-4c22adc6-cc21-4f73-9bf5-5c304a0990f9.png)

this command used build the images

7 docker ps

![docker ps](https://user-images.githubusercontent.com/114742949/196528300-5ff812a2-5ce5-4eb7-8c75-768326c400f6.png)

to check the which all container running

8 docker stop container id

![docker stop container id](https://user-images.githubusercontent.com/114742949/196529590-5ebf10de-89d7-4ee2-a828-be6333704293.png)

this command is used to stop docker container

9 docker rmi -f welcome-app

![docker rmi -f forcefully delted](https://user-images.githubusercontent.com/114742949/196530296-acb0e0ad-eaf6-4776-8e95-0b471cd17981.png)

this command used to remove forcefully container


10 docker build -t shoaibakthar18nov/welcome-app .

![docker -r build shoaib18novwelcomeapp](https://user-images.githubusercontent.com/114742949/196532817-3c657464-0dc2-455c-8b2a-43e6aa7bca9a.png)


this command is used to build images with username with respect to current working directory 

11 docker push shoaibaktahar18nov/welcome-app:latest

![docker push shoai18nov](https://user-images.githubusercontent.com/114742949/196534441-668ab2ca-9e74-4d04-a3cd-a4a007e29559.png)

this command refers to repository i,e welcome-app pushing to dockerhub with user name is shoaibakthar18nov with latest one

12 docker inspect shoaibakthar18nov/welcome-app

![docker inspect ](https://user-images.githubusercontent.com/114742949/196539590-a41e77a2-f5ee-4e5e-adb8-d0ed7d86943a.png)

this command give the details about running container 

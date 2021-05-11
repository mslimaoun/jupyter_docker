# Docker image for jupyter
# Installation
## Methode 1
#### From github
- Clone the project
- Create folder netbooks
```sh 
mkdir  netbooks 
```
- Enter the folder jupyter_docker
```sh 
cd /jupyter_docker 
```
- Execute Dockerfile and run container
```sh 
docker run -it -p 8888:8888  -d -v $(pwd)/notebooks:/notebooks python_data_science
 
```
## Methode 2
#### From Docker Hub
- Create folder netbooks
```sh 
mkdir  netbooks 
```
- Pull and run the docker image
```sh 
docker run -it -p 8888:8888  -d -v $(pwd)/notebooks:/notebooks medslimaoun/python_data_science


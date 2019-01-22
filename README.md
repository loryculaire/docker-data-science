# docker-data-science
docker image for data science using Anaconda

to build image run command:

`docker build -t docker-data-science .`

to run notebook run command:

`docker run --name docker-data-science -p 8888:8888 -v "$PWD/notebooks:/opt/notebooks" -d docker-data-science`

to access notebook:

go to http://localhost:8888/ 

to stop running the container:

`docker rm -f docker-data-science`


# Data Science and ML

This is my personal Jupyter docker image with all the necessary packages I need to do data science and machine learning.

##  Building
`$ ./build`

## Running
Excute this command in any directory you want to access it from Jupyter

`$ docker run --name data-science --rm -d -p 8888:8888 -v "$PWD":/home/jovyan/ $(whoami)/jupyter-pandas`

To access the notebooks

`$ docker logs data-science`

To stop the container 

`$ docker stop data-science`

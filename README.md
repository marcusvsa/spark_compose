RUN "./build-images.sh" to build the images in your local repo

RUN "docker-compose up" in the docker-compose.yml file directory

To submit your spark job, the docker-compose.yml file set the external mount point to:

spark-app: Store your jar/py file
spark-data: Store your raw or refined data

Both can be set by application.conf in your application.
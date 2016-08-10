# docker-python-text-classifier

From Dev to Ops. This is the source code for the 3 part series on building a text classifier in Python and Docker

For development use:

    docker run -it -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/datascience-notebook

For deployment use:

    docker build -t <your_docker_id>/text-classifier-service .
    docker run -it --rm -p 5000:5000 <your_docker_id>/text-classifier-service

Full guide at:
- https://medium.com/@mattvonrohr/from-dev-to-ops-building-a-text-classifier-using-python-and-docker-part-1-docker-6de5d27a0a20#.oms7zyury
- https://medium.com/@mattvonrohr/from-dev-to-ops-building-a-text-classifier-using-python-and-docker-part-2-building-a-simple-c664992defdc#.37xfp8rov
- https://medium.com/@mattvonrohr/from-dev-to-ops-building-a-text-classifier-using-python-and-docker-part-3-building-a-web-911d88477989#.w8220w7hn

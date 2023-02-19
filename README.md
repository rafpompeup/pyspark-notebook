# pyspark-notebook
pyspark and notebook

Install Docker on Linux

    $ sudo apt-get install docker-ce docker-ce-cli


Clone repository line command 

    $ git clone https://github.com/rafpompeup/pyspark-notebook.git
    $ cd pyspark-notebook


Run the docker command
    $ docker run -it  -p 8888:8888 -v /home/$pwd/jupyter:/home/jovyan/work jupyter/pyspark-notebook
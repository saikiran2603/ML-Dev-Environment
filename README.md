# ML-Dev-Environment
Example of a development environment setup when using NVIDIA Docker toolkit, and Tensorflow-gpu for ML development.

## Building the docker image. 

Run below command to build the docker containers with required libraries 
    
    docker-compose build

## Launch Jupyter notebook for your development environment.

    docker-compose up 

You would see something like this in console log, use the link to open notebook 

    tf-docker_1  | [I 16:27:47.506 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
    tf-docker_1  | [C 16:27:47.511 NotebookApp] 
    tf-docker_1  |     
    tf-docker_1  |     To access the notebook, open this file in a browser:
    tf-docker_1  |         file:///root/.local/share/jupyter/runtime/nbserver-1-open.html
    tf-docker_1  |     Or copy and paste one of these URLs:
    tf-docker_1  |         http://cf64133c6103:8888/?token=ea6a26036b2ee55b9cd562f675f90214e0ceec4076a250b4
    tf-docker_1  |      or http://127.0.0.1:8888/?token=ea6a26036b2ee55b9cd562f675f90214e0ceec4076a250b4

## Adding libraries. 

To add libraries to your environment add them to requirements.txt file inside tf-docker folder.



    
# docker_image_with_github_actions
docker image with github actions deployment to dockerhub

Project Step by Step Guide
##  Project file structure and setup
* Create repo for project
* clone into local environment in ide
* create files - requirements.txt, DockerFile, app.py, test_app.py, .github/workflows/cicd.yml file
* create seperate env for your project and install requirements.txt
````
conda deactivate
conda create -p venv python==3.10
conda activate venv/
pip install -r requirements.txt

```

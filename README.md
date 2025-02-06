# CoreText

This is an end-to-end Natural Language Processing (NLP) project on making a text summarizer.

Order of updating...

1. Config.yaml
2. params.yaml
3. entity
4. configuration.py in src config
5. components
6. pipeline
7. main.py
8. app.py

   ECR repo to store/save docker image

   EC2 machine (Ubuntu)

   Open EC2 and Install docker in EC2 Machine:
   #optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

Configure EC2 as self-hosted runner:

Setup github secrets

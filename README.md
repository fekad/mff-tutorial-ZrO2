# mff-tutorial-ZrO2

## Documetation:
To read the full documentation the mff package: https://mff.readthedocs.io/en/latest/


## Usage:

- The easiest way to use the docker image:
```bash
git clone https://github.com/kcl-tscm/mff-tutorial-ZrO2.git
cd mff-tutorial-ZrO2
docker run  -p 8888:8888 -v "$PWD":/home/jovyan/work --name mff-notebook fekad/mff
```
Note: The offical jupyter image was used as a base image so you can find more options at the following link: 
https://jupyter-docker-stacks.readthedocs.io/en/latest/ 


## Links:
- https://github.com/kcl-tscm/mff
- https://hub.docker.com/r/fekad/mff/

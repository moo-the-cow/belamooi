# belamooi
rework of belaui in docker

this has to be done ON the jetson:

you might wanna install samba so that you can access it via network share on windows and edit files with an editor of your choice

## Setup

put all files into a directory like /home/[username]/docker/belaui

modify the `data/BelaUI.json` to your actual environment stuff (IP, etc.)

modify the `.env` file with the actual paths of your belacoder, srtla path etc.

start it via

`docker-compose up -d` in the directory of the docker-compose.yml file

access it via http://[jetsonip]:5553

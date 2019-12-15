# plex-docker

## Instructions
Create a symlink from mounted drive to the `/movies` folder

## Mount Drive
`sudo mount /dev/sda1 /media/pi/storage/`

## Create symlink
`ln -s /media/pi/storage/ ./movies`

## Run
`docker-compose up -d`

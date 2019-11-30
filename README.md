# wordpress-setup-with-docker
sets up a wordpress site with docker

## Instructions
1. Ensure that Docker is installed and running
2. Ensure that docker-compose is installed (https://docs.docker.com/compose/install/)
3. Stop all running containers by running `docker stop $(docker ps -aq)`
4. Navigate to a location on yoru machine and clone this repo `git@github.com:shaunzo/wordpress-setup-with-docker.git`
5. Rename the cloned folder to your project name and navigate into it `./cd <PROJECT NAME>`
5. To initiate installtion run `docker-compose up`
6. Remove tracking to this repo as is just a setup start for your site:
   If Mac or Linux machine: `rm -rf .git*`
   If Windows: `del /F /S /Q /A .git` then `rmdir .git`
6. Navigate to http://localhost to view site and complete registration

## Php Admin
To view mySQL database go to `http://localhost:8080`
Your username and password will simply be `root` for localhost

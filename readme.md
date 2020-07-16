# INTRODUCTION

This will be a series of docker container images 
that can be used to quickly standup servers 


# CONTAINER v1
This image automatically renews a free SSL certificate every 6 months.
It will be used in conjunction with the reverse proxy image, allowing
1 step operation to start up a server, get NGINX going and then route 
traffic to a running docker container


# TO DO
Ideally I want a docker-compose file to spin up an environment
that can be responsive to the presence of new docker containers
There are services like this already on github, but at present 
I do not understand them.

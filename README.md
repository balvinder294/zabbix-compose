# Zabbix-compose
Zabbix in Docker Compose with PostgreS, Graffana and Adminer

## Steps for running
1. Put the configuration in a file and save with name docker-compose.yml. To keep separate create folder with name you want and put the compose file in that folder. This folder you can use for running docker-compose.
2. Open Terminal and cd to folder you created and then run command
docker-compose up -d
or if you prefer logs to be shown, then
docker-compose up
3. Now access Zabbix UI at port 8090(replace this port with your port if you have changed in above compose file). Open this url in browser
http://localhost:8090
4. Now login by entering username , password for default Admin user with credentials.
username : Admin
password: zabbix
5. Now you are setup and will reach dashboard with various tiles for information.

6. So now you can do monitoring with zabbix.
I hope this one I shared with you will be worthy, I will share later topics in new post later. Feel free to comment your opinion about my post.


## Read more in Blog post : [Link](https://medium.com/@erbalvindersingh/setting-up-and-running-zabbix-along-with-nginx-and-postgresql-using-docker-compose-2b1f011b0ba6)

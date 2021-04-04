# mig-demoapp
mig-demoapp 

Secret
================
echo "supersecretpassword" | docker secret create db_password 

Deploying the app in swarm cluster
=====================================
docker stack deploy -c docker-compose.yml demoapp

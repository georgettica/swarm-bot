## Manage Docker Swarm deployment 

swarm-bot will help to to provision new swarm cluster with docker-machine.  Simple you can manage deploy with this bash script.

### Environments

swarm-bot allow to manage multiple environments. Right now its support to manage dev, staging and production environment.  Each environment will have dedicated config file under deploy folder. E.g deploy/dev.sh, deploy/staging.sh and deploy/production.sh.  All server related configuration will be maintained here.


### Create Swarm Cluster and adding  new node



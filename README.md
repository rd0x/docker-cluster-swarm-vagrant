# Docker Cluster using Swarm and Vagrant<br>

Create a folder /local-cluster-swarm-vagrant<br>
Git clone "https://github.com/denilsonbonatti/docker-projeto2-cluster.git<br>
cd docker-projeto2-cluster/"<br>
code . * You may need to change the <i>networks</i> config, insert your ip (keep the xxx.xxx.xxx. model, using xxx.xxx.xxx.100 only for the master host).<br>
vagrant up.<br>
vagrant ssh master.<br>
docker node ls.<br>

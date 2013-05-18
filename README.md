<strong>Vagrant and Puppet configuration for NodeJS, Redis & MongoDB</strong>

Vagrant configuration with puppet to create a Virtual Box machine with Ubuntu Server 12.10, Nodejs v0.10.7, Redis 2.6.13 and MongoDB 2.4.3


Installation:<br>
Install Vagrant 1.2.2<br>
Install Virtual Box 4.2.12<br>
Clone the repository git clone https://github.com/danielcsgomes/vagrant-puppet-python-mongo.git<br>

Run - vagrant up<br>
SSH - vagrant ssh<br>
Halt - vagrant halt<br>



access mongo and redis from your machine:<br>
redis.cli h 192.168.33.10 -p 6379<br>
mongo 192.168.33.10



Puppet Manifest will install:
[Nodejs v0.10.7, Redis 2.6.13, MongoDB 2.4.3, wget, git, vim, htop]



Good hacking!!!!!!!!


thanks to Daniel Gomes (https://github.com/danielcsgomes)

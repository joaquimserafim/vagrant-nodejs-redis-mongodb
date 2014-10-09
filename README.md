<h2>Vagrant and Puppet configuration for NodeJS, Redis & MongoDB</h2>

Vagrant configuration with puppet to create a Virtual Box machine with 
Ubuntu Server 14.04, Nodejs / Redis / MongoDB




**installation:**

* Install Vagrant
* Install Virtual
* Clone the repository git clone [git://github.com/joaquimserafim/vagrant-nodejs-redis-mongodb.git](git://github.com/joaquimserafim/vagrant-nodejs-redis-mongodb.git)


**running:**

* Run - vagrant up<br>
* SSH - vagrant ssh<br>
* Halt - vagrant halt<br>




**access mongo and redis from your machine:**

* redis.cli h localhost -p 6379
* mongo localhost 27017

*attention: you may have this ports occupied by your installations for redis and mongodb in your machine*



**development:**

by default this vagrantfile have this configuration for shared folder between the host and the VM
*[config.vm.synced_folder "~/Projects", "/vagrant"](https://github.com/joaquimserafim/vagrant-nodejs-redis-mongodb/blob/master/Vagrantfile#L25)*



**Puppet Manifest will install:**

* [n](https://github.com/visionmedia/n) a node.js version management
* Redis - last stable release
* MongoDB - 2.6.\*
* wget
* git
* vim htop
* g++



Good hacking!!!!!!!!

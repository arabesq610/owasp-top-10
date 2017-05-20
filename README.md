OK Forget all that, and from https://www.linode.com/docs/applications/containers/how-to-install-docker-and-deploy-a-lamp-stack...
`$ sudo docker run -p 80:80 -t -i linode/lamp /bin/bash`



1. Install virtualbox and vagrant if you haven't already; then...
2. `$ vagrant box add bento/fedora-25`, or see [HashiCorp's Atlas box catalog](https://atlas.hashicorp.com/boxes/search?_ga=2.180367406.803294449.1494117131-1807345509.1494115466)3. `$ vagrant init bento/fedora-25; vagrant up --provider virtualbox`
3. `$ vagrant init williamyeh/ubuntu-trusty64-docker; vagrant up --provider virtualbox`
found https://vagrantcloud.com/williamyeh/boxes/ubuntu-trusty64-docker


4. `$ vagrant up`
5. `$ vagrant ssh`



The above is from 2017-05-06, and the latest set of open tabs is:

1. [Docker basics on Vagrant site](https://www.vagrantup.com/docs/docker/basics.html)
2. From Basit: [AWS Docker img](https://hub.docker.com/_/amazonlinux/)
3. [Fedora Vagrant Docker](https://developer.fedoraproject.org/tools/vagrant/vagrant-docker.html)
4. [Pure NodeJS client implementing the MySQL protocol](https://github.com/mysqljs/mysql)
5. [Testing for NoSQL Injection](https://www.owasp.org/index.php/Testing_for_NoSQL_injectioin)
6. https://www.veracode.com/security/sql-injection
7. https://www.vagrantup.com/docs/docker/basics.html
8. https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
9. https://github.com/mattdesl/module-best-practices#module-basics

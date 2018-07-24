# Adwerx Dev Ops Code Challenge

## Core Exercise: Vagrant & Virtual Box

Using Virtual Box and Vagrant, provision an Ubuntu 16.04 server using an [Ansible, Chef, or Puppet] playbook. The box should be provisioned with nginx and a Ruby application server that displays "Hello World".

### Success:
* ```vagrant up``` provisions the vagrant box
* "Hello World!" appears when visiting http://localhost:9090 on the host.
* Your files are either in a private github repo or zipped up and emailed

## Extra Credit: Docker

Using Docker, create a Ruby on Rails application that serves "Hello World!". Use docker-compose to connect the following services:
  * the new Ruby on Rails app
  * nginx as a reverse proxy to the application
  * a MySQL database

### Success:
Running `docker-compose up` should:
* Make the application accessible at http://localhost
* Make the database accessable through localhost port 3306
* Your files are either in a private github repo or zipped up and emailed.
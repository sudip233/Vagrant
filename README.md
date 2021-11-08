# Vagrant
Ruby On Rails/ Configuration of Vagrant
First,
Use hashicorp/bionic64 vagrant box because this application was tested

Ruby On Rails
- Installation of Hashicorp Vagrant
- Installation of Virtual Machine
- Configure to have static ssh port for this vagrant box
- Run the rails server and Make it accessible from the local machine.

Configuration of Virtual Box having private and public network which can be accessed from the localmachine
- Configure both private and public network for vagrant box.
- Install apache and ngnix web server both at same time with different port and must run on background and also restart if there is any process failure.
- Any of them can be moniter the status if it is running or not from systemmd or any other tools.
- Install mysql database in vagrant box and configure a user and password for a specific user and pwd.

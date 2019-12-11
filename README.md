# Magento 2 Vagrant Environment
```sh
$ git clone https://github.com/johnperricruz/magento2-vagrant-environment.git
```
Local Details : 

  - URL:  http://magento2.2.local/
  - IP: 192.168.56.159
  - MAIL : http://magento2.2.local:8025


Local Database :
  - Mysql host     : 127.0.0.1
  - user     : magento2.2
  - password : root
  - database : magento2.2


Connecting to SequelPro via SSH :
  - SSH Host     :192.168.56.159
  - user     : vagrant
  - password : ~/.vagrant.d/insecure_private_key


### Configuration

Add to hostfile : 192.168.56.159 magento2.2.local

```sh
$ cd {path_to_Vagrantfile}
$ vagrant up
$ vagrant ssh
```

### Folder Structure

```sh
./magento2.2 => Magento 2.2 Web Files
./shared => Config / Shared Files
```

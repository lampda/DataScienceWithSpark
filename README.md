# DataScienceWithSpark
Based on the hugely popular Data Science Toolbox, but with Apache Spark included. To use just clone this repository to obtain the Vagrantfile.
```
git clone https://github.com/choerst/DataScienceWithSpark.git
```

For everything to work, you will need to install Vagrant (https://www.vagrantup.com/downloads.html) and Virtualbox (https://www.virtualbox.org/wiki/Downloads) on your machine.

Navigate to the directory containing the VagrantFile and execute
```
vagrant up
```
Afterwards, ssh into the machine and start the Ipython Notebook
```
vagrant ssh
```

Inside the vagrant box execute
```
/home/vagrant/startIpython.sh
```
  
Navigate your regular browser to: https://127.0.0.1:8888/

The default password is 'science', feel free to change it by invoking the command (Inside the vagrant box)
```
dst setup base
```

For more documentation, feel free to visit the page of the original creators: http://datasciencetoolbox.org/

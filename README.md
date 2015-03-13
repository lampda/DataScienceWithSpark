# DataScienceWithSpark
Based on the hugely popular Data Science Toolbox, but with Apache Spark included
To use just clone this repository with the VagrantFile.
```
git clone https://github.com/choerst/DataScienceWithSpark.git
```

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
  
Navigate your regular browser to https://localhost:8888/
The default password is 'science', feel free to change it by invoking the command (Inside the vagrant box)
```
dst setup base
```

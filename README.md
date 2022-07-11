# Mongodb documentation

>https://docs.mongodb.com/

# mongodb installation for ubuntu lts 20.4

# Mongodb

>kishan@kishan25:~$ sudo apt install mongodb

>kishan@kishan25:~$ sudo systemctl status mongodb

>kishan@kishan25:~$ mongod --version

>kishan@kishan25:~$ mongo

>start service - kishan@kishan25:~$ sudo service mongodb start

or- >kishan@kishan25:~$ sudo systemctl status mongodb

>stop service - kishan@kishan25:~$ sudo service mongodb stop

>check status - kishan@kishan25:~$ sudo service mongodb status

# Mongodb Compass
>download first link-https://www.mongodb.com/try/download/compass

>mongodb-compass_1.29.5_amd64.deb

>kishan@kishan25:~/Downloads$ sudo dpkg -i mongodb-compass_1.29.5_amd64.deb   

# Connect mongodb to mongodb compass
1> sudo service mongodb start

2>kishan@kishan25:~$ mongo

3>copy connecting to: mongodb://127.0.0.1:27017

4>and paste in mongodb compass

mongod is the "Mongo Daemon" it's basically the host process for the database. When you start mongod you're basically saying "start the MongoDB process and run it in the background". mongod has several default parameters, such as storing data in /data/db and running on port 27017.

mongo is the command-line shell that connects to a specific instance of mongod. When you run mongo with no parameters it defaults to connecting to the localhost on port 27017. If you run mongo against an invalid machine:port combination then it will fail to connect (and tell you as much).

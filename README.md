# mongodb installation for ubuntu lts 20.4

# mongodb

>kishan@kishan25:~$ sudo apt install mongodb

>kishan@kishan25:~$ sudo systemctl status mongodb

>kishan@kishan25:~$ mongod --version

>kishan@kishan25:~$ mongo

>start service - kishan@kishan25:~$ sudo service mongodb start

or- >kishan@kishan25:~$ sudo systemctl status mongodb

>stop service - kishan@kishan25:~$ sudo service mongodb stop

>check status - kishan@kishan25:~$ sudo service mongodb status

# mongodb compass
>download first link-https://www.mongodb.com/try/download/compass

>mongodb-compass_1.29.5_amd64.deb

>kishan@kishan25:~/Downloads$ sudo dpkg -i mongodb-compass_1.29.5_amd64.deb   

# connect mongodb to mongodb compass
1> sudo service mongodb start

2>kishan@kishan25:~$ mongo

3>copy connecting to: mongodb://127.0.0.1:27017

4>and paste in mongodb compass

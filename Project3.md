# MEAN IMPLEMENTATION 
---
MEAN Implementation is used for deploying a typical application, it is an acronym which stands for 
* M - MongoDB which is a database which stores and allows to retrieve data. 
* E - stands for Express; It is a back-end application framework which helps to handle database for read and write purposes.   
* A - Angular which is a front-end web framework
* N - Node which is the back-end web framework.


### INSTALLATION OF NODE.JS 
---
The first step is to install Node.js . But it is imperative that the server is kept update using these code

`sudo apt update`
`sudo apt upgrade`

Then, the certificates are then installed.

* `sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates `

*   s`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash`.


1. To install Node.js, I had to first, create a directory called Mean-project then afterwards create an virtual environment, however, the ubuntu EC2 instance does not have the pip package, hence, I had to install it using this command `sudo apt install python3-pip`  and afterwards used this command to install node.js environment  using `sudo pip nodeenv`.

![node](./images/nodeenv.png)

### INSTALLATION OF EXPRESS.JS

1. The next step is to install MongoDB which is a database that stores data in a flexible, usually in a JSON-format documents. It is important to mention; that fields in the database vary from documents to document as well as data structure which changed over time.
The following commands were ran.

    `sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`


    `echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

The next step is to use these commands to install MongDB. 
`sudo apt install -y mongodb`
`sudo service mongodb start`
`sudo systemctl status mongodb`
`sudo apt install -y npm`

For express to effective read data from the body of the html documents, we have to install body parser modules.

`sudo npm install body-parser`

2. The 






















###Contributors
1. Temitope Temiola

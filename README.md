# docker-compose-simple
This repository is cloned from WinterChenS/docker-compose-simple.

# How to install docker-compose in rpi 
## Step 1
```javascript
sudo apt-get update
```
## Step 2
```javascript
sudo apt-get install -y python python-pip
```

## Step 3
```javascript
pip install docker-compose
```

## Step 4
```javascript
cd /usr/local/lib/python2.7/dist-packages
cp -r backports /usr/local/lib/python2.7/dist-packages/docker/transport
sudo apt install ipython
```
## Step 5
```javascript
sudo docker-compose version
```

## How to install mysql in rpi
clone https://github.com/doctormacky/docker-compose-simple/tree/master/rpi-docker-mysql
into your local, and then update the configuration file in my.cnf.
Then, sudo docker-compose up

```javascript
  var ihubo = {
    nickName  : "doctormacky",
    site : "https://github.com/doctormacky"
  }
```

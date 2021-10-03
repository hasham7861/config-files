## Description
- Mongo server config for your computer

## Config Setup Guide
- Make sure you have mongodb community installed from brew taps
- Make sure mongod is a defined command in global scope of your mac
- Then to run mongo server locally, first copy this file to like this `/etc/mongod.conf`
- Then in your cli, execute this `sudo mongod -config="/etc/mongod.conf`
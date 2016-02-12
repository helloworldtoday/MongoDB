# MongoDB

The practice of MongoDB from a beginner

## Concepts
1. document: like row in SQL
2. collection: like table in SQL

## Install (Linux platform)
1. download: `curl -O https://fastdl.mongodb.org/osx/mongodb-osx-x86_64-3.2.1.tgz`
2. extract: `tar -zxvf mongodb-osx-x86_64-3.2.1.tgz`
3. move to specific folder: `mv mongodb-osx-x86_64-3.2.1/ /usr/local/mongodb`
4. add to the path: `export PATH=<mongodb-install-directory>/bin:$PATH`
in this case, it is `export PATH=/usr/local/mongodb/bin:$PATH`
5. create new folder to store data: `mkdir -p /data/db`
6. open connection: `./mongod`
7. start up the mongodb: `./mongo` in a new shell

## Start
1. `cd /usr/local/mongodb/bin`
2. `./mongo`

# MongoDB, NodeJS - Build a todo API with authentication and relational database.

## install mongodb to your machine

- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

in your terminal

1. wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -

2. echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/ mongodb-org/ 4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list

3. sudo apt-get update

4. sudo apt-get install -y mongodb-org

5. sudo systemctl start mongod

6. sudo systemctl status mongod

## install Robo 3t from appstore

# Make sure to rename sample.end to .env and add your credentials

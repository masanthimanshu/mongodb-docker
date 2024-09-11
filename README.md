# Mongodb database deployed using docker compose

### Step 1

Clone this repository by running

```
git clone https://github.com/masanthimanshu/mongodb-docker.git
```

### Step 2

Run this command to run the docker container

```
sudo docker-compose up --build -d
```
### Step 3

Check the running docker container using

```
sudo docker ps
```
If this command ran successfully then you will see two running docker containers with the name `mongo` and `mongo-express`

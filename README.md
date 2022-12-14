# CNSP Challenge Task - Group 7

## About

A simple ToDo list app based on MySQL and NodeJS for the challenge task of Computer Network Security at UZH in 2022. 
With the ToDo list app the user can create, checkmark or delete items on a publicly reachable list. 

## How to run

```
git clone https://github.com/Sinns/CNSP_CT.git
cd CNSP_CT
docker network create proxy
docker-compose up -d
```

Afterwards the app can be reached via `https://todoapp.localhost`

The mails sent from the 2FA system are stored in the file `/CNSP_CT/authelia/config/notification.txt` and are needed to connect Google Authenticator.


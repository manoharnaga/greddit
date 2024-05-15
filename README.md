# Greddit
## A social media MERN app like Reddit 

### Frontend: [Click Here!](https://github.com/manoharnaga/gredditFrontend "Click Here!")
### Backend: [Click Here!](https://github.com/manoharnaga/gredditBackend "Click Here!")

### Things Used:
- MERN Stack
- Firebase
- Docker


</br>

## To Run Code: 

### With Docker:
1. Download Frontend and Backend repos and docker-compose.yaml, file from this repo.
2. Rename and Arrange them as:
```
gredditfrontend/
│   Dockerfile
│   package.json
│   ...
└───src/
    │   index.js
    │   ...
gredditbackend/
│   Dockerfile
│   package.json
│   ...
└───index.js
docker-compose.yaml
```

4. Then **cd** to root(.) and run as follows:
```
- sudo docker compose up --build    # To start create the docker-network with containers
- sudo docker compose down          # To stop and remove all the containers
- it's NOT docker-compose as it's V2
```

### Without Docker:
Run the backend code first
### Backend:
```
- npm i
- npm start
```

### Frontend:
```
- npm i
- npm start
```
</br>

# dockerized-react-nginx-app
<div>
    <img src="https://img.shields.io/badge/nginx-3000-green">
    <img src="https://img.shields.io/badge/reactapp-8080-blue">
</div>

Already setup and containerized react app with an nginx proxy

# Easy setup

After git-cloning the project and checked Docker and docker-compose are installed just run :

```
    docker-compose up -d
```

You can access live logs using 

```
    docker-compose logs --follow
```

These are stored in `logs/nginx`

Your react app is now running on `port 8080`
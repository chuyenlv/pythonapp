# Python app connect mogo

## Setup
```
docker-compose build
docker-compose up -d
```

## Point your browser to: 
```http://localhost:5000```

## Update more packages for python app
* Define package in file `requirements.txt`
* `docker-compose stop && docker-compose rm -f && docker-compose build && docker-compose up -d`

## Sample Application
```
docker run -d --name=redis redis
docker run -d --name=db postgres:9.4
docker run -d --name=vote -p 5000:80 --link redis:redis docker/example-voting-app-vote
docker run -d --name=result -p 5001:80 --link db:db docker/example-voting-app-result
docker run -d --name=worker --link db:db --link redis:redis docker/example-voting-app-worker

docker stop $(docker ps -a -q)
```

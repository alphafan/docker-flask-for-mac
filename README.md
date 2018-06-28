# docker-flask-for-mac

Docker flask quick deployment for mac

To build the image
```
docker build -t flask .
```

To run the flask app in docker.
```
docker run -p 5000:80 --volume=/Users/yufan/Documents/workspace/flaskdocker:/app flask
```

Open browser localhost:5000, and volia.

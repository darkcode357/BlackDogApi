## black_dog_api

## Run the Application

```
python app.py

```

This will start the application on port 5000

## Test the application

Swagger-UI can be used to test the application.
![alt text](sample-flask-application.png)

The server will start at <http://localhost:5003>.

## DockerFile
It also contain the DockerFile . In case we need to deploy it with Docker.
```
#todo
docker build -t darkcode0x00/black_dog_api .
docker run -d -p 5000:5000 darkcode0x00/black_dog_api:latest

```
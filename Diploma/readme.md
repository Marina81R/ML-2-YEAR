Diploma
http://0.0.0.0:8888/?visitorid=3

docker build -t diploma .

docker run -d -p 8888:8888 diploma diploma

To stop the web-app:
docker ps -a
docker stop <docker_id>

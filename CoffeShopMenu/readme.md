docker build -t coffeshopmenu .
docker run -d -p 8080:80 coffeshopmenu

open http://localhost:8080//
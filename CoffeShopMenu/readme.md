# build Docker image
docker build -t coffeshopmenu .

# Run the docker image and exposing it to the port 8080
docker run -d -p 8080:80 coffeshopmenu

# Access the webpage using the below link
open http://localhost:8080//
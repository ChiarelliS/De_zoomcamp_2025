to set up kestra from terminal:
docker run --pull=always --rm -it -p 8080:8080 --user=root \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v /tmp:/tmp kestra/kestra:latest server local

to set up using the docker-compose yaml:

docker-compose up (be sure to first set the directory to where the docker-compose file is)
then set up the port 8080 and open the link from github codespace ports
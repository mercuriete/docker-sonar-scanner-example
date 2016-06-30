# docker-sonar-scanner-example
usage example of docker-sonar-scanner

1) Create a Dockerfile with this inside in the same folder of your project:
FROM mercuriete/sonar-scanner:onbuild

2) Have a look into the docker-compose.yml

3) start a sonar instance somehow.

4) start the sonar-scanner container.
  This container tries to scan the code and then it connects to sonar to write report.
  

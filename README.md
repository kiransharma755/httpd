# httpd
stuff related to httpd

 docker build -t httpd .
 docker run -d -p 7000:80 httpd
 
Deleting all container running or stopped

 docker ps -qa|while read cont; do  docker rm $cont; done


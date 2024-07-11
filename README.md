
docker login
docker tag eazybytes/accounts:s11 nagaraj2023/accounts:s11
docker tag eazybytes/loans:s11 nagaraj2023/loans:s11
docker tag eazybytes/cards:s11 nagaraj2023/cards:s11
docker tag eazybytes/configserver:s11 nagaraj2023/configserver:s11

docker tag eazybytes/eurekaserver:s11 nagaraj2023/eurekaserver:s11
docker tag eazybytes/gatewayserver:s11 nagaraj2023/gatewayserver:s11

 docker tag <image> <newName>/<repoName>:<tagName>
 docker tag $ID creack/node:latest
 docker tag nagaraj2023/accounts:s11 eazybytes/accounts:s11
 docker tag nagaraj2023/accounts:s11 accounts/eazybytes:s11
docker image tag d583c3ac45fd myname/server:latest
docker image tag 84244639e5ba eazybytes/accounts:s11
docker image tag 7638f3b7245b eazybytes/loans:s11
docker image tag 4dc5bacd862f eazybytes/cards:s11
docker image tag 43c16d69a97b eazybytes/configserver:s11
docker image tag 4dc5bacd862f eazybytes/eurekaserver:s11
docker image tag 4dc5bacd862f eazybytes/gatewayserver:s11
  
--succes
docker image push docker.io/nagaraj2023/accounts:s11
docker image push docker.io/nagaraj2023/cards:s11
docker image push docker.io/nagaraj2023/loans:s11
docker image push docker.io/nagaraj2023/configserver:s11
docker image push docker.io/nagaraj2023/eurekaserver:s11
docker image push docker.io/nagaraj2023/gatewayserver:s11

docker image pull nagaraj2023/accounts:s11
docker image pull nagaraj2023/cards:s11
docker image pull nagaraj2023/loans:s11
docker image pull nagaraj2023/configserver:s11
docker image pull nagaraj2023/eurekaserver:s11
docker image pull nagaraj2023/gatewayserver:s11

preresquest :
    git
    docker 
    docker-compose

steps:

step 1 :- clone repo
git clone https://github.com/TheSwordBreaker/dockerphpmysql.git

step 2 :- move in folder
cd dockerphpmysql

step 3 :- build image
sudo docker-compose build

step 4 :- run containers
sudo docker-compose up -d

step 5 :- open browers hit localhost:80

step 6 :- stop containers
sudo docker-compose stop


Commands :-

git clone https://github.com/TheSwordBreaker/dockerphpmysql.git
cd dockerphpmysql
sudo docker-compose build
sudo docker-compose up -d


sudo docker-compose stop

preresquest :

linux
    
    git
    docker :-
        sudo apt-get update
        sudo apt-get remove docker docker-engine docker.io
        sudo apt install docker.io
        sudo systemctl start docker
        sudo systemctl enable docker
        docker --version

        sudo usermod -aG docker ${USER}

    docker-compose
        sudo curl -L https://github.com/docker/compose/releases/download/1.21.2/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
        sudo chmod +x /usr/local/bin/docker-compose
        docker-compose --version
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

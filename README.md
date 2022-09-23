# pte-docker
root@sdombi-docker-demo:/home/linux# history
    1  apt update
    2  apt-get install     ca-certificates     curl     gnupg     lsb-release
    3   sudo mkdir -p /etc/apt/keyrings
    4   curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
    5  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/debian \
    6    $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
    7  apt udpate
    8  apt upda
    9  apt update
   10   sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
   11  docker pull nginx
   12  docker images
   13  docker run nginx
   14  docker run -d nginx
   15  docker ps
   16  docker ps
   17  docker rm 4f6
   18  docker stop 4f6
   19  docker rm 4f6
   20  cd
   21  vim .bashrc
   22  PS1="$"
   23  docker images
   24  PS1=" $"
   25  docker images
   26  docker run -d nginx
   27  docker exec -it 6db ps aux
   28  docker run -d ubuntu
   29  docker exec -it d37 ps aux
   30  docker run -d ubuntu sleep 120
   31  docker exec -it 908 ps aux
   32  docker ps | grep ubuntu
   33  docker ps
   34  docker rmi ubuntu
   35  docker rm -f d37a6d93b9d7
   36  docker rmi ubuntu
   37  docker rmi -f ubuntu
   38  docker run -d ubuntu sleep 120
   39  docker ps | grep ubuntu
   40  docker run -d -p 8080:80 nginx:latest
   41  docker exec -it 7a0 bash
   42  curl https://localhost:8080
   43  curl http://localhost:8080
   44  docker ps
   45  docker stop 7a0
   46  docker rm 7a0
   47  docker run -d nginx bash
   48  docker rm ace
   49  docker ps
   50  docker run -it nginx bash
   51  PS1=" $"
   52  docker ps
   53  docker run -it nginx bash
   54  docker commit bf7cb my-nginx:1.0
   55  docker images
   56  docker run -d -p 8080:80 my-nginx:1.0
   57  curl http://localhost:8080
   58  curl http://localhost:8080
   59  docker ps\
   60  docker ps
   61  docker run -d -p 8080:80 my-nginx:1.0 sleep 120
   62  curl http://localhost:8080
   63  docker run -d -p 8080:80 my-nginx:1.0
   64  docker ps -a
   65  docker ps
   66  curl http://localhost:8080
   67  docker ps
   68  docker ps
   69  docker inspect 6db | less
   70  cd\
   71  cd
   72  mkdir source
   73  touch source/code.yml
   74  docker run -it -v $PWD/source/:/srv/ nginx
   75  rm -f source/
   76  rm -rf source/
   77  mkdir source
   78  touch source/code.yml
   79  docker run -d -v $PWD/source/:/srv/ nginx
   80  docker exec -it 82b8 ls -l /srv
   81  echo "hello world" source/code.yml
   82  echo > "hello world" source/code.yml
   83  docker exec -it 82b8 cat /srv/code.yml
   84  cat source/code.yml
   85  echo "hello world" > source/code.yml
   86  docker exec -it 82b8 cat /srv/code.yml
   87  mkdir docker
   88  cd docker/
   89  ls -lah
   90  vim Dockerfile
   91  PS1=" $ "
   92  ls -l
   93  docker build . -t sdombi/my-redis
   94  vim Dockerfile
   95  docker build . -t sdombi/my-redis
   96  rm Dockerfile
   97  ls -lah
   98  wget https://github.com/docker/getting-started/archive/refs/heads/master.zip
   99  ls -lah
  100  unzip master.zip
  101  ls -lah
  102  cd getting-started-master/
  103  ls -lah
  104  vim Dockerfile
  105  cd app/
  106  ls -lah
  107  ls -l src/
  108  vim Dockerfiles
  109  vim Dockerfile
  110  docker build . -t sdombi/node-app
  111  vim Dockerfile
  112  #docker run –e MYSQL_USER=db_user –e MYSQL_PASSWORD=${m_password} –e MYSQL_DATABASE=my_db –e MYSQL_ROOT_PASSWORD=${m_root_password} –d mysql:latest
  113  docker run –e MYSQL_USER=db_user –e MYSQL_PASSWORD=${m_password} –e MYSQL_DATABASE=my_db –e MYSQL_ROOT_PASSWORD=${m_root_password} –d mysql:latest
  114  docker run –e MYSQL_USER=db_user –e MYSQL_PASSWORD=my_pass –e MYSQL_DATABASE=my_db –e MYSQL_ROOT_PASSWORD=root_pass –d mysql:latest
  115  docker run -e MYSQL_USER=db_user -e MYSQL_PASSWORD=my_pass -e MYSQL_DATABASE=my_db -e MYSQL_ROOT_PASSWORD=root_pass -d mysql:latest
  116  docker ps
  117  docker exec -it 80949f616a9f bash
  118  docker exec -it 80949f616a9f bash
  119  history

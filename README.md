# development
Settingup of local development machine
git -v
$ docker -v
$ docker-compose -v
$ git clone git@bitbucket.com:<project>/development.git <project> && cd <project>
$ git submodule init && git submodule update
$ git submodule foreach npm install
$ docker-compose up -d

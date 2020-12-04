dockerのインストール
$ sudo yum install -y yum-utils
$ sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
$ sudo yum-config-manager --enable docker-ce-edge
$ sudo yum makecache fast
$ sudo yum install -y docker-ce
$ sudo systemctl start docker
$ sudo systemctl enable docker
$ sudo docker run hello-world

docker composeのインストール
$ sudo -i
# curl -L https://github.com/docker/compose/releases/download/1.25.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
# chmod +x /usr/local/bin/docker-compose
# exit
$ docker-compose --version

docker-compose.ymlが存在するディレクトリ下で
$ docker-compose up -d

PowerDNS-Adminへのアクセス
htpp://localhost:docker-compose.ymlで設定した値



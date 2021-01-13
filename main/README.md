# PowerDNS & PowerDNS-Admin & db
 
PowerDNS & PowerDNS-Admin & dbのかんたんな起動
  
# Installation
 
dockerのインストール
 
```bash
$ sudo yum install -y yum-utils
$ sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
$ sudo yum-config-manager --enable docker-ce-edge
$ sudo yum makecache fast
$ sudo yum install -y docker-ce
$ sudo systemctl start docker
$ sudo systemctl enable docker
$ sudo docker run hello-world
```

docker composeのインストール
```bash
$ sudo -i
# curl -L https://github.com/docker/compose/releases/download/1.25.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
# chmod +x /usr/local/bin/docker-compose
# exit
$ docker-compose --version
```


# Usage
 
gitからファイルの入手
 
```bash
git clone https://github.com/HSRNetwork/docker-powerdns-admin
cd docker-powerdns-admin
docker-compose up -d
```
# アクセス方法
http://localhost:docker-compose.ymlで設定したポート番号
 
# Note
 
ソースの方のymlファイルでは、コンテナ名などが設定されていなかったので追加した.
また、パスワードなど適宜変更しなければならない点がある.
 




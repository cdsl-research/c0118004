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
 
# Usage
 
DEMOの実行方法など、"hoge"の基本的な使い方を説明する
 
```bash
git clone https://github.com/hoge/~
cd examples
python demo.py
```
 
# Note
 
注意点などがあれば書く
 
# Author
 
作成情報を列挙する
 
* 作成者
* 所属
* E-mail
 
# License
ライセンスを明示する
 
"hoge" is under [MIT license](https://en.wikipedia.org/wiki/MIT_License).
 
社内向けなら社外秘であることを明示してる
 
"hoge" is Confidential.



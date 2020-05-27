# Install oracle-java8-installer и oracle-java8-set-default:

* Download this repo 
```
cd /root
git clone https://github.com/kautMaks/oracle-java8-installer.git
cd https://github.com/kautMaks/oracle-java8-installer.git
```
* Make debs
```sh
dpkg-deb -b oracle-java8-installer_8u251-99_amd64/ oracle-java8-installer_8u251-99_amd64.deb
dpkg-deb -b oracle-java8-set-default_8u251-99_amd64/ oracle-java8-set-default_8u251-99_amd64.deb
```
* Install debs
```
apt-get install ./oracle-java8-installer_8u251-99_amd64.deb ./oracle-java8-set-default_8u251-99_amd64.deb
```
* Ptofit :)

* P.S. To get jdk and jre sources, run
```
wget -c --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u251-b08/3d5a2bb8f8d4428bbe94aed7ec7ae784/jdk-8u251-linux-x64.tar.gz
wget -c --no-cookies --no-check-certificate --header "Cookie: oraclelicense=accept-securebackup-cookie" http://download.oracle.com/otn-pub/java/jdk/8u251-b08/3d5a2bb8f8d4428bbe94aed7ec7ae784/jre-8u251-linux-x64.tar.gz
```

# setup-start-tools

A tools' list you should have installed on your new linux setup

## guake

<http://guake-project.org/>

```sh
sudo apt-get install guake
```

## sdkman

<https://sdkman.io/>

```sh
sudo apt install curl wget unzip -y
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk version
```

```console
$ sdk version
==== BROADCAST =================================================================
* 2021-02-27: pomchecker 1.1.0 available on SDKMAN!
* 2021-02-27: pomchecker 1.1.0 available on SDKMAN! https://github.com/kordamp/pomchecker/releases/tag/v1.1.0
* 2021-02-26: kotlin 1.4.31 available on SDKMAN!
================================================================================

SDKMAN 5.11.0+644
```

### java

<https://www.java.com/fr/>

```sh
sdk list java
sdk install java 11.0.10-open
```

```console
$ java --version
openjdk 11.0.10 2021-01-19
OpenJDK Runtime Environment 18.9 (build 11.0.10+9)
OpenJDK 64-Bit Server VM 18.9 (build 11.0.10+9, mixed mode)
```

### gradle

<https://gradle.org/>

```sh
sdk install gradle
```

```console
$ gradle -v

Welcome to Gradle 6.8.3!
```

### maven

<https://maven.apache.org/>

```sh
sdk install maven
```

```console
$ mvn -v
Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
Maven home: /home/rsoutart/.sdkman/candidates/maven/current
Java version: 11.0.10, vendor: Oracle Corporation, runtime: /home/rsoutart/.sdkman/candidates/java/11.0.10-open
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "5.8.0-44-generic", arch: "amd64", family: "unix"
```

## nvm

<https://github.com/nvm-sh/nvm>

```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```

```console
$ nvm -v
0.37.2
```

### node

<https://nodejs.org/>

```sh
nvm install node
```

> `node` come with the latest compatible [`npm`](https://www.npmjs.com/) version

## yarn

<https://yarnpkg.com/>

```sh
sudo npm install --global yarn
```

```console
$ yarn -v
1.22.5
```

## tree

```sh
sudo apt install tree
```

```console
$ tree .
├── Desktop
├── Documents
│   ├── docs
│   │   └── cheatsheet-must-have-tools.md
```

## docker

<https://www.docker.com/>

```sh
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo apt-key fingerprint 0EBFCD88
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
sudo apt-get update
sudo apt-get install docker-ce docker-ce-cli containerd.io
```

```console
$ docker run hello-world

Hello from Docker!
This message shows that your installation appears to be working correctly.
...
```

### user permissions

```sh
sudo groupadd docker
sudo usermod -aG docker $USER
```

### docker-compose

```sh
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

```console
$ docker-compose -v
docker-compose version 1.28.4, build cabd5cfb
```

## vagrant

<https://www.vagrantup.com/>

Download file : <https://releases.hashicorp.com/vagrant/2.2.14/vagrant_2.2.14_x86_64.deb>

```sh
sudo apt install ./vagrant_2.2.14_x86_64.deb
```

```console
$ vagrant --version
Vagrant 2.2.14
```

## microk8s

<https://microk8s.io/>

```sh
sudo snap install microk8s --classic
```

> Using [`snap`](https://snapcraft.io/)

```console
$ microk8s status --wait-ready
microk8s is running
```

### permissions

```sh
sudo usermod -a -G microk8s rsoutart
sudo chown -f -R rsoutart ~/.kube
```

## google chrome

<https://www.google.com/chrome/>

```sh
sudo apt-get install google-chrome-stable
```

## slack

<https://slack.com>

```sh
sudo snap install slack --classic
```

> Using [`snap`](https://snapcraft.io/)

# setup-start-tools

A tools' list you should have installed on your new linux setup

![git](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/git/square-1-60.png)
![terminal](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/t/terminal/square-1-60.png)
![sdkman](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/s/sdkman/square-1-60.png)
![java](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/j/java/square-1-60.png)
![gradle](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/gradle/square-1-60.png)
![maven](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/m/maven/square-1-60.png)
![nodejs](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/n/nodejs/square-1-60.png)
![npm](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/n/npm/square-1-60.png)
![yarn](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/y/yarn/square-1-60.png)
![tree](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/t/terminal/square-1-60.png)
![docker](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/d/docker/square-1-60.png)
![docker-compose](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/d/docker-compose/square-1-60.png)
![guake](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/guake/square-1-60.png)
![virtualbox](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/v/virtualbox/square-1-60.png)
![vagrant](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/v/vagrant/square-1-60.png)
![slack](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/s/slack/square-1-60.png)

## git

<https://git-scm.com/>

*"Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency."*

```sh
sudo apt install git-all
```

## curl

<https://curl.se/>

*"curl is used in command lines or scripts to transfer data. curl is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations."*

```sh
sudo apt install curl
```

## sdkman

<https://sdkman.io/>

*"SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems."*

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

## java

<https://www.java.com/>

*"Java allows you to play online games, chat with people around the world, calculate your mortgage interest, and view images in 3D, just to name a few. It's also integral to the intranet applications and other e-business solutions that are the foundation of corporate computing."*

> Using [sdkman](https://sdkman.io/jdks#jdk.java.net)

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

## gradle

<https://gradle.org/>

*"Gradle is an open-source build automation tool focused on flexibility and performance."*

> Using [sdkman](https://sdkman.io/sdks#gradle)

```sh
sdk install gradle
```

```console
$ gradle -v

Welcome to Gradle 6.8.3!
```

## maven

<https://maven.apache.org/>

*"Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information."*

> Using [sdkman](https://sdkman.io/sdks#maven)

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

*"nvm is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL."*

```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```

```console
$ nvm -v
0.37.2
```

## node

<https://nodejs.org/>

*"As an asynchronous event-driven JavaScript runtime, Node.js is designed to build scalable network applications."*

> Using [nvm](https://github.com/nvm-sh/nvm)

```sh
nvm install node
```

> `node` come with the latest compatible [`npm`](https://www.npmjs.com/) version

## yarn

<https://yarnpkg.com/>

*"Yarn is a package manager that doubles down as project manager. Whether you work on one-shot projects or large monorepos, as a hobbyist or an enterprise user, we've got you covered.*"

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

*"Docker simplifies and accelerates your workflow, while giving developers the freedom to innovate with their choice of tools, application stacks, and deployment environments for each project."*

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

## docker-compose

*"Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services."*

```sh
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

```console
$ docker-compose -v
docker-compose version 1.28.4, build cabd5cfb
```

## guake

<http://guake-project.org/>

*"Guake is a top-down terminal for Gnome, and is highly inspirated by the famous terminal used in Quake."*

```sh
sudo apt-get install guake
```

## virtualbox

<https://www.virtualbox.org/>

*"VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use."*

```sh
sudo apt install virtualbox
```

## vagrant

<https://www.vagrantup.com/>

*"HashiCorp Vagrant provides the same, easy workflow regardless of your role as a developer, operator, or designer. It leverages a declarative configuration file which describes all your software requirements, packages, operating system configuration, users, and more."*

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

*"Low-ops, minimal production Kubernetes,
for devs, cloud, clusters, workstations, Edge and IoT."*

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

*"Google builds powerful tools that help you connect, play, work and get things done. And all of it works on Chrome."*

```sh
sudo apt-get install google-chrome-stable
```

## slack

<https://slack.com>

*"Slack is the collaboration hub that brings the right people, information, and tools together to get work done."*

```sh
sudo snap install slack --classic
```

> Using [`snap`](https://snapcraft.io/)

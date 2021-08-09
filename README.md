# setup-start-tools

A tools' list you should have installed on your new linux setup

[![git](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/git/square-1-60.png)](#git "git")
[![terminal](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/t/terminal/square-1-60.png)](#curl "curl")
[![sdkman](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/s/sdkman/square-1-60.png)](#sdkman "sdkman")
[![java](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/j/java/square-1-60.png)](#java "java")
[![gradle](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/gradle/square-1-60.png)](#gradle "gradle")
[![maven](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/m/maven/square-1-60.png)](#maven "maven")
[![nodejs](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/n/nodejs/square-1-60.png)](#nodejs "nodejs")
[![terminal](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/t/terminal/square-1-60.png)](#nvm "nvm")
[![npm](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/n/npm/square-1-60.png)](#npm "npm")
[![yarn](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/y/yarn/square-1-60.png)](#yarn "yarn")
[![tree](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/t/terminal/square-1-60.png)](#tree "tree")
[![docker](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/d/docker/square-1-60.png)](#docker "docker")
[![docker-compose](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/d/docker-compose/square-1-60.png)](#docker-compose "docker-compose")
[![guake](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/g/guake/square-1-60.png)](#guake "guake")
[![virtualbox](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/v/virtualbox/square-1-60.png)](#virtualbox "virtualbox")
[![vagrant](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/v/vagrant/square-1-60.png)](#vagrant "vagrant")
[![slack](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/s/slack/square-1-60.png)](#slack "slack")
[![mattermost](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/m/mattermost/square-1-60.png)](#mattermost "mattermost")
[![intellij](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/i/intellij/square-1-60.png)](#intellij "intellij")
[![postgresql](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/p/postgresql/square-1-60.png)](#postgresql "postgresql")
[![dbeaver](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/d/dbeaver/square-1-60.png)](#dbeaver "dbeaver")
[![postman](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/p/postman/square-1-60.png)](#postman "postman")
[![vscode](https://github.com/HakumenNC/logo-gallery/raw/0.0.4/img/v/vscode/square-1-60.png)](#vscode "vscode")

## git

<https://git-scm.com/>

*"Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency."*

```sh
sudo apt install git-all
```

[Back to top](#setup-start-tools)

## curl

<https://curl.se/>

*"curl is used in command lines or scripts to transfer data. curl is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations."*

```sh
sudo apt install curl
```

[Back to top](#setup-start-tools)

## sdkman

<https://sdkman.io/>

*"SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems."*

```sh
sudo apt install curl wget unzip -y
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk version
```

[Back to top](#setup-start-tools)

## java

<https://www.java.com/>

*"Java allows you to play online games, chat with people around the world, calculate your mortgage interest, and view images in 3D, just to name a few. It's also integral to the intranet applications and other e-business solutions that are the foundation of corporate computing."*

> Using [sdkman](https://sdkman.io/jdks#jdk.java.net)

```sh
sdk list java
sdk install java 11.0.10-open
```

```sh
java --version
```

[Back to top](#setup-start-tools)

## gradle

<https://gradle.org/>

*"Gradle is an open-source build automation tool focused on flexibility and performance."*

> Using [sdkman](https://sdkman.io/sdks#gradle)

```sh
sdk install gradle
```

```sh
gradle -v
```

[Back to top](#setup-start-tools)

## maven

<https://maven.apache.org/>

*"Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information."*

> Using [sdkman](https://sdkman.io/sdks#maven)

```sh
sdk install maven
```

```sh
mvn -v
```

[Back to top](#setup-start-tools)

## nvm

<https://github.com/nvm-sh/nvm>

*"nvm is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL."*

```sh
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash
```

```sh
nvm -v
```

[Back to top](#setup-start-tools)

## node

<https://nodejs.org/>

*"As an asynchronous event-driven JavaScript runtime, Node.js is designed to build scalable network applications."*

> Using [nvm](https://github.com/nvm-sh/nvm)

```sh
nvm install node
```

> `node` come with the latest compatible [`npm`](https://www.npmjs.com/) version

[Back to top](#setup-start-tools)

## yarn

<https://yarnpkg.com/>

*"Yarn is a package manager that doubles down as project manager. Whether you work on one-shot projects or large monorepos, as a hobbyist or an enterprise user, we've got you covered.*"

```sh
sudo npm install --global yarn
```

```sh
yarn -v
```

[Back to top](#setup-start-tools)

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

[Back to top](#setup-start-tools)

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

```sh
docker run hello-world
```

### user permissions

```sh
sudo groupadd docker
sudo usermod -aG docker $USER
```

[Back to top](#setup-start-tools)

## docker-compose

*"Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services."*

```sh
sudo curl -L "https://github.com/docker/compose/releases/download/1.28.4/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```

```sh
docker-compose -v
```

[Back to top](#setup-start-tools)

## guake

<http://guake-project.org/>

*"Guake is a top-down terminal for Gnome, and is highly inspirated by the famous terminal used in Quake."*

```sh
sudo apt-get install guake
```

[Back to top](#setup-start-tools)

## virtualbox

<https://www.virtualbox.org/>

*"VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use."*

```sh
sudo apt install virtualbox
```

[Back to top](#setup-start-tools)

## vagrant

<https://www.vagrantup.com/>

*"HashiCorp Vagrant provides the same, easy workflow regardless of your role as a developer, operator, or designer. It leverages a declarative configuration file which describes all your software requirements, packages, operating system configuration, users, and more."*

Download file : <https://releases.hashicorp.com/vagrant/2.2.14/vagrant_2.2.14_x86_64.deb>

```sh
sudo apt install ./vagrant_2.2.14_x86_64.deb
```

```sh
vagrant --version
```

[Back to top](#setup-start-tools)

## microk8s

<https://microk8s.io/>

*"Low-ops, minimal production Kubernetes,
for devs, cloud, clusters, workstations, Edge and IoT."*

```sh
sudo snap install microk8s --classic
```

> Using [`snap`](https://snapcraft.io/)

```sh
microk8s status --wait-ready
```

### permissions

```sh
sudo usermod -a -G microk8s rsoutart
sudo chown -f -R rsoutart ~/.kube
```

[Back to top](#setup-start-tools)

## google chrome

<https://www.google.com/chrome/>

*"Google builds powerful tools that help you connect, play, work and get things done. And all of it works on Chrome."*

```sh
sudo apt-get install google-chrome-stable
```

[Back to top](#setup-start-tools)

## slack

<https://slack.com>

*"Slack is the collaboration hub that brings the right people, information, and tools together to get work done."*

```sh
sudo snap install slack --classic
```

> Using [`snap`](https://snapcraft.io/)

[Back to top](#setup-start-tools)

## mattermost

<https://mattermost.com/>

*"Bring your tools and teams together in a fully secure location."*

```sh
sudo snap install mattermost-desktop
```

> Using [`snap`](https://snapcraft.io/)

[Back to top](#setup-start-tools)

## intellij

<https://www.jetbrains.com/idea/>

*"Every aspect of IntelliJ IDEA has been designed to maximize developer productivity. Together, intelligent coding assistance and ergonomic design make development not only productive but also enjoyable."*

ultimate

```sh
sudo snap install intellij-idea-ultimate --classic --edge
```

community

```sh
sudo snap install intellij-idea-community --classic --edge
```

> Using [`snap`](https://snapcraft.io/)

[Back to top](#setup-start-tools)

## postgresql

<https://www.postgresql.org/>

*"PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance."*

```sh
sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'
wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
sudo apt-get update
sudo apt-get -y install postgresql-9.6
```

[Back to top](#setup-start-tools)

## dbeaver

<https://dbeaver.io/>

*"Free multi-platform database tool for developers, database administrators, analysts and all people who need to work with databases."*

```sh
sudo add-apt-repository ppa:serge-rider/dbeaver-ce
sudo apt-get update
sudo apt-get install dbeaver-ce
```

[Back to top](#setup-start-tools)

## postman

<https://www.postman.com/>

*"Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster."*

```sh
sudo snap install postman
```

> Using [`snap`](https://snapcraft.io/)

[Back to top](#setup-start-tools)

## vscode

<https://code.visualstudio.com/>

*"Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux."*

```sh
sudo snap install code --classic
```

> Using [`snap`](https://snapcraft.io/)

[Back to top](#setup-start-tools)

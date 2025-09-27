# setup-start-tools

A curated list of essential tools to install on a fresh Linux setup ([Ubuntu](https://ubuntu.com/desktop) in this example)

![linux](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/l/linux/rectangle-b-1-40.png)
![ubuntu](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/u/ubuntu/rectangle-b-1-40.png)

Looking for more logos? Explore the complete collection [here](https://github.com/HakumenNC/logo-gallery)!

[Coding](#coding) | [Databases & tools](#databases--tools) | [Infrastructures & virtualizations](#infrastructures--virtualizations) | [IDE](#ide) | [Network](#network) | [Collaboration apps](#collaboration-apps) | [Utilities](#utilities)

## Coding

|Tools|Description|
|:---:|:---|
|![git](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/g/git/square-b-1-60.png) <br /> git|*"Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency."* <br /><br /> <https://git-scm.com> \| [Installation](https://git-scm.com/downloads/linux) |
|![curl](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/t/terminal/square-b-1-60.png) <br /> curl|*"curl is used in command lines or scripts to transfer data. curl is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations."* <br /><br /> <https://curl.se> \| [Installation](https://everything.curl.dev/install/linux.html#ubuntu-and-debian) |
|![snapcraft](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/s/snapcraft/square-b-1-60.png) <br /> snapcraft|Snaps are app packages for desktop, cloud and IoT that are easy to install, secure, cross‐platform and dependency‐free. Snaps are discoverable and installable from the Snap Store, the app store for Linux with an audience of millions. <br /><br /> <https://snapcraft.io> \| [Installation](https://snapcraft.io/docs/installing-snap-on-ubuntu)|

### With [SDKMAN!](https://sdkman.io)

|Tools|Description|
|:---:|:---|
|![sdkman](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/s/sdkman/square-b-1-60.png) <br /> sdkman|*"SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems."* <br /><br /> <https://sdkman.io> \| [Installation](https://sdkman.io/install)|
|![java](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/j/java/square-b-1-60.png) <br /> java|*"Java allows you to play online games, chat with people around the world, calculate your mortgage interest, and view images in 3D, just to name a few. It's also integral to the intranet applications and other e-business solutions that are the foundation of corporate computing."* <br /><br /> <https://www.java.com> \| [Installation](https://sdkman.io/sdks#java) *(using [sdkman](https://sdkman.io))* |
|![gradle](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/g/gradle/square-b-1-60.png) <br /> gradle|*"Gradle is an open-source build automation tool focused on flexibility and performance."* <br /><br /> <https://gradle.org> \| [Installation](https://sdkman.io/sdks#gradle) *(using [sdkman](https://sdkman.io))*|
|![maven](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/m/maven/square-b-1-60.png) <br /> maven|*"Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information."* <br /><br /> <https://maven.apache.org> \| [Installation](https://sdkman.io/sdks#maven) *(using [sdkman](https://sdkman.io))*|
|![other](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/set/other/square-1-60.png?raw=true) <br /> other|*Discover more available SDKs* <br /><br /> [SDK's list](https://sdkman.io/sdks)

### With [nvm](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)

|Tools|Description|
|:---:|:---|
|![nvm](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/t/terminal/square-b-1-60.png) <br /> nvm|*"nvm is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL."* <br /><br /> <https://github.com/nvm-sh/nvm> \| [Installation](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)|
|![nodejs](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/n/nodejs/square-b-1-60.png) <br /> nodejs|*"As an asynchronous event-driven JavaScript runtime, Node.js is designed to build scalable network applications."* <br /><br /> <https://nodejs.org> \| [Installation](https://github.com/nvm-sh/nvm?tab=readme-ov-file#intro) *(using [nvm](https://github.com/nvm-sh/nvm))*|
|![npm](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/n/npm/square-b-1-60.png) <br /> npm|*"npm is the world's largest software registry. Open source developers from every continent use npm to share and borrow packages, and many organizations use npm to manage private development as well."* <br /><br /> <https://www.npmjs.com> \| ~~Installation~~ *(come with [nodejs](https://nodejs.org) installation)*|

### Javascript package manager *(other than [npm](https://www.npmjs.com))*

|Tools|Description|
|:---:|:---|
|![yarn](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/y/yarn/square-b-1-60.png) <br /> yarn|*"Yarn is a package manager that doubles down as project manager. Whether you work on one-shot projects or large monorepos, as a hobbyist or an enterprise user, we've got you covered.*" <br /><br /> <https://yarnpkg.com> \| [Installation](https://yarnpkg.com/getting-started/install)|
|![bower](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/b/bower/square-b-1-60.png) <br /> bower|*"Bower can manage components that contain HTML, CSS, JavaScript, fonts or even image files. Bower doesn’t concatenate or minify code or do anything else - it just installs the right versions of the packages you need and their dependencies.*" <br /><br /> <https://bower.io> \| [Installation](https://bower.io/#install-bower)|

### Python

|Tools|Description|
|:---:|:---|
|![python](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/p/python/square-b-1-60.png) <br /> python|*"Python can be easy to pick up whether you're a first time programmer or you're experienced with other languages. The following pages are a useful first step to get on your way writing programs with Python!*" <br /><br /> <https://www.python.org> \| [Installation](https://docs.python.org/3/using/unix.html)|
|![jupyter](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/j/jupyter/square-b-1-60.png) <br /> jupyter|*"**JupyterLab:** [...] JupyterLab is the latest web-based interactive development environment for notebooks, code, and data. [...]. **Jupyter Notebook:** [...] The Jupyter Notebook is the original web application for creating and sharing computational documents. [...]*" <br /><br /> <https://jupyter.org> \| [Installation](https://jupyter.org/install)|

[Back to top](#setup-start-tools)

## Databases & tools

|Tools|Description|
|:---:|:---|
|![postgresql](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/p/postgresql/square-b-1-60.png) <br /> postgresql|*"PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance."* <br /><br /> <https://www.postgresql.org> \| [Installation](https://www.postgresql.org/download/linux/ubuntu/)|
|![dbeaver](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/d/dbeaver/square-b-1-60.png) <br /> dbeaver|*"Free multi-platform database tool for developers, database administrators, analysts and all people who need to work with databases."* <br /><br /> <https://dbeaver.io> \| [Installation](https://dbeaver.io/download/)|

[Back to top](#setup-start-tools)

## Infrastructures & virtualizations

|Tools|Description|
|:---:|:---|
|![docker](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/d/docker/square-b-1-60.png) <br /> docker|*"Docker simplifies and accelerates your workflow, while giving developers the freedom to innovate with their choice of tools, application stacks, and deployment environments for each project."* <br /><br /> <https://www.docker.com> \| [Installation](https://docs.docker.com/engine/install/ubuntu/) + [Docker Compose](https://docs.docker.com/compose/)|
|![portainer](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/p/portainer/square-b-1-60.png) <br /> portainer|*"Portainer Community Edition 2.0 is the foundation of the Portainer world. With over half a million regular users, it’s a powerful, open source toolset that allows you to easily build and manage containers in Docker, Docker Swarm, Kubernetes and Azure ACI.."* <br /><br /> <https://www.portainer.io> \| [Installation](https://docs.portainer.io/start/install-ce/server/docker/linux)|
|![microk8s](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/m/microk8s/square-b-1-60.png) <br /> microk8s|*"MicroK8s is an open-source system for automating deployment, scaling, and management of containerised applications. It provides the functionality of core Kubernetes components, in a small footprint, scalable from a single node to a high-availability production cluster."* <br /><br /> <https://microk8s.io> \| [Installation](https://microk8s.io/docs/getting-started)|
|![virtualbox](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/v/virtualbox/square-b-1-60.png) <br /> virtualbox|*"VirtualBox is a general-purpose full virtualization software for x86_64 hardware (with version 7.1 additionally for macOS/Arm), targeted at laptop, desktop, server and embedded use."* <br /><br /> <https://www.virtualbox.org> \| [Installation](https://www.virtualbox.org/wiki/Linux_Downloads)|
|![vagrant](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/v/vagrant/square-b-1-60.png) <br /> vagrant|*"Vagrant is the command line utility for managing the lifecycle of virtual machines. Isolate dependencies and their configuration within a single disposable and consistent environment."* <br /><br /> <https://developer.hashicorp.com/vagrant> \| [Installation](https://developer.hashicorp.com/vagrant/install#linux)|

[Back to top](#setup-start-tools)

## IDE

|Tools|Description|
|:---:|:---|
|![intellij](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/i/intellij/square-b-1-60.png) <br /> intellij|*"Every aspect of IntelliJ IDEA has been designed to maximize developer productivity. Together, intelligent coding assistance and ergonomic design make development not only productive but also enjoyable."* <br /><br /> <https://www.jetbrains.com/idea> \| [Installation](https://snapcraft.io/intellij-idea-ultimate) + [Community Edition](https://snapcraft.io/intellij-idea-community)|
|![vscode](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/v/vscode/square-b-1-60.png) <br /> vscode|*"Visual Studio Code is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux."* <br /><br /> <https://code.visualstudio.com> \| [Installation](https://snapcraft.io/code)|

[Back to top](#setup-start-tools)

## Network

|Tools|Description|
|:---:|:---|
|![forticlient](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/f/forticlient/square-b-1-60.png) <br /> forticlient|*"The VPN-only version of FortiClient offers SSL VPN and IPSecVPN, but does not include any support. Download the best VPN software for multiple devices."* <br /><br /> <https://www.fortinet.com/support/product-downloads> \| [Installation](https://www.fortinet.com/support/product-downloads#vpn)|
|![remmina](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/r/remmina/square-b-1-60.png) <br /> remmina|*"Remote access screen and file sharing to your desktop."* <br /><br /> <https://remmina.org> \| [Installation](https://remmina.org/how-to-install-remmina/#snap)|
|![filezilla](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/f/filezilla/square-b-1-60.png) <br /> filezilla|*"The FileZilla Client not only supports FTP, but also FTP over TLS (FTPS) and SFTP. It is open source software distributed free of charge under the terms of the GNU General Public License."* <br /><br /> <https://filezilla-project.org> \| [Installation](https://wiki.filezilla-project.org/Client_Installation)|

[Back to top](#setup-start-tools)

## Collaboration apps

|Tools|Description|
|:---:|:---|
|![slack](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/s/slack/square-b-1-60.png) <br /> slack|*"Slack is the collaboration hub that brings the right people, information, and tools together to get work done."* <br /><br /> <https://slack.com> \| [Installation](https://snapcraft.io/slack)|
|![discord](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/d/discord/square-b-1-60.png) <br /> discord|*"Discord is great for playing games and chilling with friends, or even building a worldwide community. Customize your own space to talk, play, and hang out."* <br /><br /> <https://discord.com> \| [Installation](https://discord.com/download)|
|![mattermost](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/m/mattermost/square-b-1-60.png) <br /> mattermost|*"One platform for technical and operational teams to collaborate across every workflow."* <br /><br /> <https://mattermost.com> \| [Installation](https://docs.mattermost.com/deploy/desktop/linux-desktop-install.html)|

[Back to top](#setup-start-tools)

## Utilities

|Tools|Description|
|:---:|:---|
|![chrome](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/c/chrome/square-b-1-60.png) <br /> chrome|*"The browser built to be safe"* <br /><br /> <https://www.google.com/chrome> \| [Installation](https://support.google.com/chrome/answer/95346?hl=en&ref_topic=7439538&sjid=3744390017485772053-NC#zippy=%2Clinux)|
|![postman](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/p/postman/square-b-1-60.png) <br /> postman|*"Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster."* <br /><br /> <https://www.postman.com> \| [Installation](https://snapcraft.io/postman)|
|![httpie](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/h/httpie/square-b-1-60.png) <br /> httpie|*"HTTPie—aitch-tee-tee-pie—is a user-friendly command-line HTTP client for the API era. It comes with JSON support, syntax highlighting, persistent sessions, wget-like downloads, plugins, and more.*" <br /><br /> <https://httpie.io> \| [Installation](https://httpie.io/docs/cli/debian-and-ubuntu)|
|![tree](https://raw.githubusercontent.com/HakumenNC/logo-gallery/v0.2.18/img/t/terminal/square-b-1-60.png) <br /> tree|`sudo apt install tree`|

[Back to top](#setup-start-tools)


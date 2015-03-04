# Just-Quizzing-Vagrant
Vagrant file for a local [Just Quizzing Server](https://github.com/claudiu-persoiu/Just-Quizzing-Server).

## Installation
- Download and install Vagrant (https://www.vagrantup.com/)

- clone the repository recursively in a local folder

`git clone --recursive https://github.com/claudiu-persoiu/Just-Quizzing-Vagrant.git`

- go to the directory

`$ cd Just-Quizzing-Vagrant`

- run the image

`vagrant up`

- when the script will finish you should be able to access the platform at `http://192.168.56.19` or `http://localhost:8080` (make sure port 8080 is open on the local machine or change it to another value in Vagrantfile)

- from the mobile app (https://play.google.com/store/apps/details?id=ro.claudiupersoiu.just.quizzing) it will be your local ip folowed by port (e.g. `192.168.0.100:8080`).

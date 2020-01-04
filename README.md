# install-docker on ubuntu 

## install python virtualenv on ubuntu
```shell script 
    git clone https://github.com/system-dev-formations/install-docker.git
    cd install-docker/
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get install python3 python3-pip python3-venv
    python3 -m venv venv
    source venv/bin/activate
    python -V
```
## install ansible on localhost in virtualenv 
```shell script
   pip3 install wheel
   pip3 install ansible
   ansible --version
```
## run docker install using ansible 
```shell script
   ansible-playbook -i inventory playbook
```


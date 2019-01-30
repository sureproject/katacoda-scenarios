## วิธีการติดตั้ง kubectl

ติดตั้ง kubectl โดยใช้คำสั่งต่อไปนี้

`sudo apt-get update && sudo apt-get install -y apt-transport-https`{{execute}}

`curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -`{{execute}}

`echo "deb https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee -a /etc/apt/sources.list.d/kubernetes.list`{{execute}}

`sudo apt-get update`{{execute}}

`sudo apt-get install -y kubectl`{{execute}}


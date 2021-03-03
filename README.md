# Docker App for Get SH>IT Done!

Get SH>IT Done Carrousel - Docker App (2021)


## Install Docker on Amazon Linux 2
> sudo yum update -y

> sudo amazon-linux-extras install -y docker

> sudo service docker start

> sudo usermod -a -G docker ec2-user

> sudo systemctl enable docker

> docker info



## Download the code and Build the container
> sudo yum install -y git

> git clone https://github.com/Juli-BCN/get-shit-done-docker.git

> cd get-shit-done-docker

> docker build -t get-sh-it-done .

> docker images
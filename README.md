# Twenty
HOST OPEN SOURCE TWENTY CRM ON YOUR OWN UBUNTU OR ANY SERVER | LIFETIME FREE CRM | IN JUST 8 MINTS

//+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
/The Comment To Install  Docker and Docker Composer In Ubuntu 20.04.6 LTS
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. sudo apt update && sudo apt upgrade -y
2. sudo apt install -y ca-certificates curl gnupg lsb-release
3. sudo mkdir -p /etc/apt/keyrings
4. curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo tee /etc/apt/keyrings/docker.asc > /dev/null
5. sudo chmod a+r /etc/apt/keyrings/docker.asc
6. echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
7. sudo apt update
8. sudo apt install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
9. sudo systemctl enable docker
10.sudo systemctl start docker
11.docker --version
12.docker compose version


//+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
/The Comment To Install Twenty CRM In Ubuntu 20.04.6 LTS
//++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

1. bash <(curl -sL https://git.new/20)
2. docker compose up -d

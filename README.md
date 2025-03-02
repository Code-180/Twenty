
#Twenty

HOST OPEN SOURCE TWENTY CRM ON YOUR OWN UBUNTU OR ANY SERVER | LIFETIME FREE CRM | IN JUST 8 MINTS


## Used By

The Comment To Install  Docker and Docker Composer In Ubuntu 20.04.6 LTS:

- sudo apt update && sudo apt upgrade -y
- sudo apt install -y ca-certificates curl gnupg lsb-release
- sudo mkdir -p /etc/apt/keyrings
- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo tee /etc/apt/keyrings/docker.asc > /dev/null
- sudo chmod a+r /etc/apt/keyrings/docker.asc
- echo "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
- sudo apt update
- sudo apt install -y docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
- sudo systemctl enable docker
- sudo systemctl start docker
- docker --version
- docker compose version

## Used By

The Comment To Install Twenty CRM In Ubuntu 20.04.6 LTS:

- bash <(curl -sL https://git.new/20)
- docker compose up -d
## Tech Stack

**Client:** Docker

**Server:** Ubuntu 20.04.6 LTS

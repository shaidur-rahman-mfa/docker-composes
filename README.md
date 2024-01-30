## Installing Docker and Docker Compose

1. Run the following command in your terminal:
```
curl -fsSL https://get.docker.com | sudo sh
```
2. After the installation is complete, add your user to the docker group:
```
sudo usermod -aG docker $USER
```
3. Log out and log back in, or restart your system to apply the group changes.

4. To install Docker Compose, run:
```
sudo curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
5. After the installation, verify that Docker and Docker Compose are installed:
```
docker --version
docker-compose --version
```

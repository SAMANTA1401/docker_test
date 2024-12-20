# Running the Application

To run the application, use the following command:
```bash
sudo apt-get update -y
```
```bash
sudo apt-get upgrade
```
```bash
curl -fsSL https://get.docker.com -o get-docker.sh
```
```bash
sudo sh get-docker.sh
```
```bash
sudo usermod -aG docker ubuntu
```
```bash
newgrp docker
```

```bash
 mkdir actions-runner && cd actions-runner
```
 ```bash
curl -o actions-runner-linux-x64-2.321.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.321.0/actions-runner-linux-x64-2.321.0.tar.gz
```
```bash
echo "ba46ba7ce3a4d7236b16fbe44419fb453bc08f866b24f04d549ec89f1722a29e  actions-runner-linux-x64-2.321.0.tar.gz" | shasum -a 256 -c
```
```bash
tar xzf ./actions-runner-linux-x64-2.321.0.tar.gz
```

```bash
tar xzf ./actions-runner-linux-x64-2.321.0.tar.gz
```

Enter the name of runner: 
```bash
self-hosted
```
```bash
./run.sh
```

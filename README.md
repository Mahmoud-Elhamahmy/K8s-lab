# K8s-lab - install minikube on linux machine

## Steps:
- install VB and run linux ubuntu machine
- Download kubectl using this url:
```bash
   curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
```
- install kubectl using this command:
```bash
   sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
```
- Download minikube using this url:
```bash
   curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```
-install kubectl using this command:
```bash
   sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
```
### Check
- run command:
```bash
   minikube start
```
- run command:
```bash
  minikube status
```
### Screenshot

![image](https://github.com/user-attachments/assets/5084a281-8f60-4080-bef6-691d9f5d9332)



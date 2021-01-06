# Instalar o mini-kube

Baixar o mini-kube

`curl -Lo minikube https://github.com/kubernetes/minikube/releases/download/v0.28.0/minikube-linux-amd64`

Ativar permissões

`chmod +x minikube`

Mover para para seu PATH

` mv minikube /usr/local/bin/`

# Instalando o kubectl

Baixar o kubectl

`curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"`

Ativar permissões

`chmod +x ./kubectl`

Mover para para seu PATH

`sudo mv ./kubectl /usr/local/bin/kubectl`
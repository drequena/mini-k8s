# Mini-curso hands-on Kubernetes.

## Para preparar o ambiente do mini-curso faça:

1. Instale o Docker no Linux (as root)
```bash
  curl -fsSL https://get.docker.com/ | sh -
```

2. Faça download do binários do Kubectl
```bash
  curl -O https://bit.ly/2AzqNwv -o kubectl
  mv kubectl /usr/local/bin/kubectl
  chmod +x /usr/local/bin/kubectl
```

3. Clone o repositório do projeto Kubernetes-Docker-in-Docker
```bash
  git clone https://github.com/richardsonlima/kubernetes-docker-in-docker-cluster.git
```
4. Suba o cluster (essa etapa pode demorar alguns minutos devido ao download da imagem do container)
```bash
  cd kubernetes-docker-in-docker-cluster
  ./NUM_NODES.sh
```

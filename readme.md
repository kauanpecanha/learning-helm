Este repositório está sendo atualizado por @kauanpecanha com o intuito de armazenar o processo de aprendizado da ferramenta Helm, do Kubernetes.

Neste projeto, a aplicação **giropops-senhas**, desenvolvida por @badtuxx ([link](https://github.com/badtuxx/giropops-senhas-labs)) está sendo utilizada como cenário deste aprendizado.

## Comandos utilizados

```
# comando para conseguir as ocorrências dos pods (passar --watch para ver atualizações em tempo real)
k get pods

# comando para conseguir as ocorrências dos serviços
k get svc

# comando para instalação do chart do giropops-senhas
helm install giropops-senhas ./chart/
```

## O que é este Chart?

Este chart Helm foi criado para facilitar o deploy e gerenciamento da aplicação **giropops-senhas** e seus componentes no Kubernetes. Ele define todos os recursos necessários, como Deployments, Services e configurações, permitindo instalar, atualizar e remover a aplicação de forma simples e padronizada.


# PostgreSQL com DigitalOcean Block Storage no Kubernetes

Este é um projeto de estudo que demonstra a implementação de um banco de dados PostgreSQL utilizando DigitalOcean Block Storage em um cluster Kubernetes.

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido com fins educacionais para demonstrar:
- Configuração de persistência de dados usando DigitalOcean Block Storage
- Deploy de PostgreSQL em ambiente Kubernetes
- Gerenciamento de volumes persistentes em cloud

⚠️ **Nota de Segurança**: Este é um projeto de estudos e não deve ser usado em produção sem as devidas adaptações de segurança.

## 🏗️ Arquitetura

A arquitetura do projeto consiste em:
- PostgreSQL 15.0 rodando em container
- Volume persistente usando DigitalOcean Block Storage
- LoadBalancer para acesso externo
- Kubernetes como orquestrador

## 🛠️ Tecnologias Utilizadas

- Kubernetes
- PostgreSQL 15.0
- DigitalOcean Block Storage
- LoadBalancer

## 📦 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/BrendoTrindade/Block-storage.git
```

2. Aplique as configurações:
```bash
kubectl apply -f deployment.yaml
```

## 📊 Configurações

- PostgreSQL:
  - Versão: 15.0
  - Porta: 5432
  - Porta Externa: 30000
- Storage:
  - Tipo: DigitalOcean Block Storage
  - Capacidade: 4GB

## 🎓 Aprendizados

- Gerenciamento de volumes persistentes no Kubernetes
- Configuração de Block Storage na DigitalOcean
- Boas práticas de deployment de banco de dados

## 👤 Autor

Brendo Trindade
- LinkedIn: [Brendo Trindade](https://www.linkedin.com/in/brendo-trindade-a57b03230/)
- GitHub: [@BrendoTrindade](https://github.com/BrendoTrindade)

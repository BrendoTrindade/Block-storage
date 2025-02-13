# PostgreSQL com Block Storage na DigitalOcean

## Visão Geral
Projeto de estudo focado na implementação de um banco de dados PostgreSQL utilizando DigitalOcean Block Storage em ambiente Kubernetes, demonstrando boas práticas de persistência de dados em ambientes containerizados.

## Desafio
O principal desafio era implementar uma solução de armazenamento persistente para um banco de dados PostgreSQL em um ambiente Kubernetes, garantindo que os dados permanecessem seguros e acessíveis mesmo após a reinicialização dos containers.

## Solução
Desenvolvi uma arquitetura utilizando:
- Kubernetes como plataforma de orquestração
- DigitalOcean Block Storage para persistência de dados
- PostgreSQL 15.0 em containers
- LoadBalancer para acesso externo

### Componentes Principais
1. **Deployment PostgreSQL**
   - Container PostgreSQL 15.0
   - Configurações de ambiente seguras
   - Gerenciamento de recursos

2. **Persistência de Dados**
   - Volume persistente com Block Storage
   - Capacidade de 4GB
   - Backup e recuperação facilitados

3. **Networking**
   - LoadBalancer configurado
   - Porta externa 30000
   - Acesso seguro ao banco de dados

## Resultados
- Implementação bem-sucedida de persistência de dados
- Ambiente de banco de dados escalável
- Documentação completa do processo
- Código fonte disponível no GitHub

## Tecnologias Utilizadas
- Kubernetes
- PostgreSQL 15.0
- DigitalOcean Block Storage
- LoadBalancer
- Git

## Lições Aprendidas
- Gerenciamento eficiente de volumes persistentes
- Configuração de Block Storage na nuvem
- Boas práticas de deployment de banco de dados
- Documentação técnica efetiva

## Links
- [Código no GitHub](https://github.com/BrendoTrindade/Block-storage)
- [Documentação Completa](https://github.com/BrendoTrindade/Block-storage/blob/main/README.md)

*Nota: Este é um projeto de estudo e demonstração, não recomendado para uso em produção sem as devidas adaptações de segurança.*

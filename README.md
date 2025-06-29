# ArgoCD Demo Repository

Este repositório contém aplicações Kubernetes gerenciadas pelo ArgoCD.

## Estrutura

- `nginx-app/` - Aplicação de exemplo com Nginx
- `guestbook/` - Aplicação Guestbook clássica

## Como usar

1. O ArgoCD monitora este repositório automaticamente
2. Qualquer mudança nos manifestos será aplicada no cluster
3. Para adicionar novas aplicações, crie uma nova pasta com os manifestos Kubernetes

## Aplicações

### nginx-app
- **Descrição**: Aplicação web simples com Nginx
- **Replicas**: 2
- **Porta**: 80
- **Tipo de serviço**: ClusterIP

### guestbook  
- **Descrição**: Aplicação Guestbook com Redis
- **Componentes**: Frontend + Redis
- **Porta**: 80

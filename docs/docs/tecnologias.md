---
sidebar_position: 3
---

# ⚙️ Tecnologias

## 🗓 Informações Gerais

- **Nome do Projeto:**
<!-- Exemplo: Sistema de Gestão de Reservas para Biblioteca -->

- **Tech Lead:**
<!-- Nome da pessoa responsável pela coordenação e entrega da parte visual do projeto -->

- **Data de Entrada na Área:**
<!-- Exemplo: 10/04/2025 -->

- **Data Estimada de Conclusão da Área:**
<!-- Exemplo: 08/06/2025 -->

- **Link para Documento de Visão de Produto:**
<!-- Exemplo: https://github.com/empresa/docs/projeto-reservas/visao.md -->

## Checklist de Entrada e Saída da Área de Tecnologia

### ✅ Checklist de Entrada

- [ ] Documento de Visão de Produto validado

### 📤 Checklist de Saída

- [ ] Stack definida e aprovada
- [ ] Diagrama de arquitetura completo
- [ ] Plano de implantação claro
- [ ] Documento validado com o time de Desenvolvimento

## Stack Tecnológica

### Frontend
- Framework/Biblioteca: 
- Linguagem principal: 
- Ferramentas adicionais:
- Justificativa da escolha:

### Backend
- Linguagem: 
- Framework: 
- ORM (se aplicável): 
- Estratégia de autenticação/autorização: 
- Justificativa da escolha:

### Banco de Dados
- Tipo (relacional/não-relacional):
- Tecnologia: 
- Justificativa da escolha:

### Outras Tecnologias
- Cache (ex: Redis):
- Fila de mensagens (ex: RabbitMQ, Kafka):
- Monitoramento e logs (ex: Datadog, Sentry):
- Testes automatizados (ex: Jest, Cypress, PyTest):
- Outras dependências relevantes:
- Justificativa da escolha:

## Arquitetura da Solução

### Visão Geral da Arquitetura

O sistema utiliza uma arquitetura MVC orientada a serviços, com back-end rodando em C# com .NET e front-end baseado em TypeScript com NextJS. Para deploy nos ambientes de desenvolvimento e produção, utilizamos docker para conteinerização e AWS como plataforma de cloud.

O back-end roda em uma instância EC2 da AWS (Amazon Elastic Computing Cloud), enquanto o deploy do front-end é feito em Vercel para uma redução de custos. Os serviços de armazenamento e banco de dados funcionam em nuvem com os serviços de Bucket do S3 (Simple Storage System) e RDS (Relational Database System) da AWS respectivamente.

### Componentes Principais
- AWS EC2
- AWS RDS
- AWS S3
- Back-end em .NET
- Front-end em NextJS
- Datadog para Logs

### Diagrama da Arquitetura (opcional)

![Diagrama de componentes](../../assets/diagrama-componentes.jpg)

## Estrutura de Implantação

### Ambiente de Desenvolvimento

* Como os devs devem subir localmente:
* Docker/Compose disponível?:
* Variáveis de ambiente principais:

### Ambiente de Produção

* URL:
* Estratégia de deploy (blue/green, canary, etc):
* Infraestrutura (ex: AWS, GCP, Heroku, Vercel, etc):
* Ferramentas de observabilidade ativas:

### Diagrama de Implantação (opcional)
> Diagrama com servidores, buckets, serviços gerenciados, DNS, CDNs, etc.

## Considerações de Segurança

* Políticas de CORS:
* Proteção de dados sensíveis (ex: criptografia, mascaramento):
* Gestão de segredos (ex: Vault, Secrets Manager):
* Autenticação e autorização:

---
sidebar_position: 2
---

# 📄 Visão de Produto

<!-- Este documento deve ser preenchido pela área de Visão de Produto para cada novo projeto. -->

## 🗓 Informações Gerais

- **Nome do Projeto:** 
Tattoo Studio — Sistema de Portfólio e Agendamento

- **Cliente:** 
João (tatuador freelancer)

- **Responsável da Visão de Produto (PO):**
Lorena Gabriela da Silva Garcia

- **Duração Total Estimada:** 
10 semanas

- **Período na Etapa de Design (estimado):** 
2 semanas

- **Período na Etapa de Desenvolvimento (estimado):** 
8 semanas

---

## ✅ Checklist de Entrada (para iniciar o projeto)

- [X] Reunião de Kickoff com o cliente realizada
- [X] Objetivo do projeto compreendido
- [X] Tecnologias necessárias mapeadas
- [X] Estimativa de esforço feita
- [X] Capacidade do time verificada
- [X] Escopo inicial aprovado pelo cliente

---

## 📤 Checklist de Saída (para encaminhar o projeto às próximas áreas)

- [X] Documento de Visão preenchido e validado
- [X] Matriz “é/não é/faz/não faz” definida
- [X] Wireframes (se aplicável) finalizados
- [X] Epics e User Stories redigidas
- [X] Datas de entrada/saída em cada área definidas
- [X] Contrato e escopo revisados e claros
- [X] Alinhamento com área de Design ou Desenvolvimento realizado

---

## 📘 Resumo do Projeto

<!-- Explique brevemente o que é o projeto, sua motivação, e o problema que resolve. -->

**Descrição:**
Desenvolver um sistema web para o tatuador João, que funcione como cartão de visitas digital e plataforma de gestão. O sistema terá um portfólio organizado por estilos de tatuagem, um módulo de agendamento de sessões com fluxo de aprovação pelo próprio tatuador, além de páginas informativas (FAQ, contato e localização).

**Objetivos:**
- Melhorar a presença online do cliente, oferecendo um site organizado e atrativo.
- Facilitar a divulgação do portfólio, permitindo a separação por estilos de tatuagem.
- Automatizar e organizar o processo de solicitação de horários, reduzindo o tempo gasto em conversas informais no WhatsApp e Instagram.
- Criar uma área administrativa intuitiva para o tatuador gerenciar portfólio, agenda e dúvidas frequentes sem necessidade de conhecimentos técnicos.

**Público-Alvo:**
- Clientes em potencial oriundos de redes sociais, interessados em conhecer os trabalhos do tatuador e realizar o agendamento de sessões
- O próprio tatuador (administrador do sistema), que utilizará a plataforma para gerenciar seu portfólio, agenda e informações de atendimento.

## 👤 Personas

- **Tatuador (Administrador do site):** É o dono do site e o principal usuário do painel de gerenciamento. Ele precisa de uma interface intuitiva para realizar suas tarefas sem a necessidade de conhecimento técnico.
    
    -  **Necessidades Principais:**
        
        -  Gerenciar seu portfólio de tatuagens: adicionar, excluir, editar suas fotos. além de poder organizá-las em categorias/estilos.
            
        -  Administrar sua agenda: visualizar horários, bloquear datas e horários manualmente.
            
        -  Receber e gerenciar solicitações de agendamento (visualizar os pedidos pendentes, aprovar ou recusar).
            
        -  Atualizar o conteúdo informativo do site (editar a página de "Dúvidas Frequentes", informações de contato e endereço).

Para complementar a visão do sistema, é fundamental definir também a persona do usuário final:

- **Cliente (Visitante do site):** É o usuário que acessa o site para conhecer o trabalho do tatuador e/ou marcar um horário com o mesmo. Ele busca uma experiência fluida, visual e direta para resolver suas necessidades.
    
    - **Necessidades Principais:**
        
        - Visualizar o portfólio do tatuador de forma organizada, com a possibilidade de filtrar por estilo.
            
        - Consultar a agenda para ver os dias e horários disponíveis.
            
        - Enviar um pedido de agendamento: preenchendo um formulário com seus dados, descrição da ideia e imagens de referência.
            
        - Acessar facilmente informações práticas: endereço do estúdio, contato e respostas para dúvidas comuns.
---

## 🧩 Matriz "É / Não É / Faz / Não Faz"
<div align="center">


| Categoria   | Descrição                                                                                                                                                                                                                                                                                                                          |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **É**       | - Um cartão de visitas digital e profissional.<br>- Uma ferramenta de portfólio para exibir trabalhos de forma organizada<br>- Um sistema para otimizar e organizar o processo de agendamento.                                                                                                                                     |
| **Não É**   | - Uma plataforma de e-commerce ou um sistema de pagamentos online.<br>- Uma ferramenta de comunicação em tempo real ou chat                                                                                                                                                                                                        |
| **Faz**     | - Exibe os trabalhos do tatuador, permitindo a filtragem por estilo<br>- Mostra aos clientes uma agenda com os horários disponíveis para tatuar<br>- Centraliza todas as solicitações em um painel administrativo para o tatuador aprovar ou recusar<br>- Permite que o tatuador bloqueie dias/horários manualmente em sua agenda. |
| **Não Faz** | - Processa pagamentos<br>- Aprova agendamentos automaticamente<br>- Gerencia as finanças do estúdio<br>- Realiza conversas em tempo real (chat)                                                                                                                                                                                    |


</div>

---


## 🧱 Epics e User Stories

### 🔹 Epics

- Epic 1: Autenticação e Cadastro no Fluxo de Agendamento
- Epic 2: Portfólio e Conteúdo Público
- Epic 3: Agenda e Solicitação de Agendamento
- Epic 4: Gestão de Solicitações

### 🔸 User Stories

#### US1
- **Usuário:** Cliente novo
- **Objetivo:** Preencher dados pessoais e informações da tatuagem ao solicitar agendamento
- **Justificativa:** Garantir que o sistema registre o pedido e crie automaticamente a conta do cliente

<br/>

#### US2
- **Usuário:** Cliente novo
- **Objetivo:** Receber e-mail com instruções para definir a senha após criação automática da conta
- **Justificativa:** Permitir que o cliente acesse futuramente seus dados e histórico de agendamentos

<br/>

#### US3
- **Usuário:** Cliente existente
- **Objetivo:** Fazer login durante a solicitação de agendamento
- **Justificativa:** Vincular o pedido à conta já existente do cliente

#### US04

- **Usuário:** Cliente
- **Objetivo:** Recuperar a senha informando o e-mail
- **Justificativa:** Possibilitar o acesso à conta em caso de esquecimento de senha

#### US05

- **Usuário:** Cliente
- **Objetivo:** Visualizar galeria de tatuagens
- **Justificativa:** Conhecer os trabalhos realizados pelo tatuador

#### US06

- **Usuário:** Cliente
- **Objetivo:** Filtrar o portfólio por categorias/estilos
- **Justificativa:** Encontrar mais facilmente o tipo de trabalho de interesse

#### US07

- **Usuário:** Cliente
- **Objetivo:** Acessar páginas de conteúdo (FAQ, Sobre, Contato)
- **Justificativa:** Obter informações práticas sobre o estúdio

#### US08

- **Usuário:** Administrador
- **Objetivo:** Gerenciar portfólio (adicionar, associar a categorias e excluir imagens)
- **Justificativa:** Manter os trabalhos organizados e atualizados

#### US09

- **Usuário:** Administrador
- **Objetivo:** Gerenciar categorias de estilos (criar, editar e excluir)
- **Justificativa:** Organizar melhor o portfólio e facilitar a navegação dos clientes

#### US10

- **Usuário:** Administrador
- **Objetivo:** Editar o conteúdo das páginas públicas (FAQ, Sobre, Contato)
- **Justificativa:** Manter as informações sempre atualizadas para os clientes

#### US11

- **Usuário:** Cliente
- **Objetivo:** Visualizar a agenda pública
- **Justificativa:** Consultar horários disponíveis antes de solicitar um agendamento

#### US12

- **Usuário:** Cliente
- **Objetivo:** Solicitar agendamento selecionando horário e preenchendo formulário
- **Justificativa:** Enviar solicitação diretamente ao tatuador

#### US13

- **Usuário:** Administrador
- **Objetivo:** Visualizar agenda completa com status dos horários (Livre, Pendente, Confirmado, Bloqueado)
- **Justificativa:** Ter controle sobre a disponibilidade e compromissos

#### US14

- **Usuário:** Administrador
- **Objetivo:** Gerenciar disponibilidade da agenda (recusar solicitações, bloquear/desbloquear horários)
- **Justificativa:** Manter controle total sobre os períodos de atendimento

#### US15

- **Usuário:** Administrador
- **Objetivo:** Visualizar no dashboard todas as solicitações pendentes
- **Justificativa:** Ter visão rápida do que precisa ser tratado

#### US16

- **Usuário:** Administrador
- **Objetivo:** Acessar detalhes completos de uma solicitação
- **Justificativa:** Avaliar a proposta do cliente antes de tomar uma decisão

---

## ⚙️ Requisitos Funcionais

<!-- 
Liste os requisitos funcionais do sistema, ou seja, o que o sistema deve fazer de forma objetiva. Pense em ações, comportamentos e regras que precisam estar presentes no produto final.

Os Requisitos Funcionais (RFs) podem ser:
- Inferidos a partir de User Stories.
- Traduções técnicas de uma US, visando o ponto de vista da implementação.
- Divisões mais específicas e técnicas de uma única US (ou seja, uma US pode originar vários RFs).

Enquanto as US estão centradas nas necessidades do usuário, os RFs são mais voltados à engenharia e ao desenvolvimento. Servem como base para orientar o time técnico na hora de implementar funcionalidades específicas.
-->

<!-- Dica 1: Numerar os requisitos ajuda na rastreabilidade durante o projeto. -->

<!-- Dica 2: Agrupar os RFs por página ou outro tipo de agrupamento pode ser muito útil. -->

<!-- 
### Exemplo de Formato:

RF01 - O sistema deve permitir que usuários se cadastrem utilizando nome, e-mail institucional e senha.
RF02 - O sistema deve permitir a criação de reservas de salas com data, horário e descrição.
RF03 - O administrador deve poder visualizar e aprovar reservas pendentes.
RF04 - O sistema deve enviar um e-mail automático de confirmação após uma reserva ser realizada.
-->

<!-- Preencha abaixo com os requisitos do seu projeto -->

### 1. Páginas Públicas 

#### Páginas de Login / Cadastro de Cliente
| ID       | Requisito            | Descrição                                                                                                                                                |
| :------- | :------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF01** | Cadastro de Cliente  | O sistema deve permitir que um novo cliente se cadastre fornecendo nome completo, e-mail, número de contato e uma senha.                                 |
| **RF02** | Login de Cliente     | O sistema deve permitir que um cliente já cadastrado realize login utilizando seu e-mail e senha.                                                        |
| **RF03** | Recuperação de Senha | O sistema deve fornecer uma funcionalidade de "Esqueci minha senha", na qual o cliente informa seu e-mail e recebe as instruções para redefinir a senha. |

#### Página de Portfólio
| ID       | Requisito                 | Descrição                                                                                                                       |
| :------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------ |
| **RF04** | Visualização do Portfólio | O sistema deve exibir uma galeria com as imagens das tatuagens cadastradas pelo administrador.                                  |
| **RF05** | Filtragem do Portfólio    | O sistema deve permitir que o usuário filtre as imagens do portfólio por categorias (estilos) pré-definidas pelo administrador. |

#### Página de Agendamento
| ID       | Requisito                      | Descrição                                                                                                                                                                                                                                                       |
| :------- | :----------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF06** | Visualização da Agenda Pública | O sistema deve exibir um calendário com os dias e horários que estão disponíveis para agendamento. Horários já ocupados ou bloqueados não devem ser selecionáveis.                                                                                              |
| **RF07** | Solicitação de Agendamento     | O sistema deve permitir que um cliente inicie uma solicitação de agendamento ao selecionar um horário disponível e preencher um formulário com nome, telefone, e-mail, descrição da sua ideia, tamanho, estilo da tatuagem e o upload de imagens de referência. |
| **RF08** | Acompanhamento do Agendamento  | O sistema deve permitir que o cliente acompanhe o andamento de seu agendamento, visualizando em uma tabela o campo Status do Agendamento, que pode estar como marcado (confirmado e ativo), cancelado (desmarcado e inválido) ou finalizado (já concluído). |
| **RF09** | Cancelamento de Agendamento    | O sistema deve permitir que o cliente cancele um agendamento já marcado por meio de um botão “Cancelar” disponível na interface de acompanhamento. Ao confirmar a ação, o status do agendamento deve ser atualizado para cancelado, e o horário correspondente deve voltar a ficar disponível na agenda pública. |


#### Fluxo de Finalização de Agendamento (Lógica de Conta)
| ID       | Requisito                                   | Descrição                                                                                                                                                                                              |
| :------- | :------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF08** | Vinculação de Solicitação à Conta Existente | Ao submeter o formulário de agendamento, se o e-mail informado já pertencer a um cliente cadastrado, o sistema deve prosseguir com a solicitação, vinculando-a à conta existente.                      |
| **RF09** | Criação de Conta via Solicitação            | Se o e-mail informado no formulário de agendamento não possuir cadastro, o sistema deve criar uma nova conta para o cliente, registrar a solicitação e notificá-lo por e-mail para que crie uma senha. |

#### Páginas de Conteúdo (FAQ, Sobre, Contato)
| ID       | Requisito                           | Descrição                                                                                                                   |
| :------- | :---------------------------------- | :-------------------------------------------------------------------------------------------------------------------------- |
| **RF10** | Visualização de Páginas de Conteúdo | O sistema deve exibir o conteúdo das páginas "FAQ", "Contato e Localização" e "Sobre", conforme editado pelo administrador. |

### 2. Painel Administrativo 

#### Página de Login do Administrador
| ID       | Requisito              | Descrição                                                                                                                        |
| :------- | :--------------------- | :------------------------------------------------------------------------------------------------------------------------------- |
| **RF11** | Login do Administrador | O sistema deve possuir uma área de login, com e-mail e senha, para acesso exclusivo do administrador ao painel de gerenciamento. |

#### Página de Dashboard Principal
| ID       | Requisito                 | Descrição                                                                                                                              |
| :------- | :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------- |
| **RF12** | Dashboard de Solicitações | O painel administrativo deve exibir, em sua tela principal, uma lista de todas as solicitações de agendamento com o status "Pendente". |

#### Página de Detalhes da Solicitação
| ID       | Requisito                   | Descrição                                                                                                                                                                                                         |
| :------- | :-------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF13** | Detalhamento da Solicitação | O administrador deve poder visualizar os detalhes completos de uma solicitação: dados do cliente, descrição da ideia e as imagens de referência.                                                                  |
| **RF14** | Aprovação de Solicitação    | O administrador deve ter a funcionalidade de "Aprovar" uma solicitação de agendamento. Ao ser aprovada, o status do horário na agenda deve mudar para "Confirmado" e o mesmo deve ser removido da agenda pública. |
| **RF15** | Recusa de Solicitação       | O administrador deve ter a funcionalidade de "Recusar" uma solicitação de agendamento. Ao ser recusada, o horário deve voltar a ficar "Livre" e disponível na agenda pública.                                     |

#### Página de Gestão da Agenda
| ID       | Requisito                       | Descrição                                                                                                                                                  |
| :------- | :------------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF16** | Visualização da Agenda Completa | O administrador deve ter acesso a uma visão de calendário completa, que exibe os status de todos os horários (ex: Livre, Pendente, Confirmado, Bloqueado). |
| **RF17** | Bloqueio Manual de Horários     | O administrador deve poder bloquear e desbloquear manualmente dias e/ou horários específicos em sua agenda, tornando-os indisponíveis na agenda pública.      |

#### Página de Gestão do Portfólio
| ID       | Requisito                          | Descrição                                                                                                     |
| :------- | :--------------------------------- | :------------------------------------------------------------------------------------------------------------ |
| **RF18** | Upload de Imagens                  | O sistema deve permitir que o administrador faça o upload de novas imagens para o portfólio.                  |
| **RF20** | Associação de Imagens a Categorias | Ao adicionar ou editar uma imagem, o administrador deve poder associá-la a uma ou mais categorias existentes. |
| **RF21** | Exclusão de Imagens                | O administrador deve poder excluir imagens existentes do portfólio.                                           |

#### Página de Gestão de Categorias
| ID       | Requisito            | Descrição                                                                                                               |
| :------- | :------------------- | :---------------------------------------------------------------------------------------------------------------------- |
| **RF19** | Gestão de Categorias | O administrador deve poder criar, editar e excluir as categorias (estilos) que serão usadas para organizar o portfólio. |

#### Página de Gestão de Conteúdo (CMS)
| ID       | Requisito                     | Descrição                                                                                                                                                          |
| :------- | :---------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **RF22** | Edição de Páginas de Conteúdo | O sistema deve fornecer um editor de texto simples para que o administrador possa criar e alterar o conteúdo das páginas "FAQ", "Contato e Localização" e "Sobre". |


## 📱 Responsividade

**O projeto será responsivo?**
- [X] Sim
- [ ] Não

**Se sim, até qual ponto?**
- [X] Mobile-first
- [ ] Adaptável para tablets
- [ ] Desktops Grandes e notebooks menores
- [ ] Totalmente responsivo (desktop, tablet, mobile)

---

## 📌 Observações Finais

<!-- Qualquer observação relevante, como restrições legais, técnicas, dependências externas ou riscos conhecidos. -->

---


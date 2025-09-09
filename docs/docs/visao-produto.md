---
sidebar_position: 2
---

# 📄 Visão de Produto

<!-- Este documento deve ser preenchido pela área de Visão de Produto para cada novo projeto. -->

## 🗓 Informações Gerais

- **Nome do Projeto:** 
Tattoo Studio — Sistema de Portfólio e Agendamento

- **Cliente:** 
Joãozinho Tatuagens (tatuador freelancer)

- **Responsável da Visão de Produto (PO):**
<!-- Nome da pessoa responsável pelo acompanhamento e comunicação com o cliente -->

- **Duração Total Estimada:** 
10 semanas

- **Período na Etapa de Design (estimado):** 
2 semanas

- **Período na Etapa de Desenvolvimento (estimado):** 
8 semanas

---

## ✅ Checklist de Entrada (para iniciar o projeto)

- [ ] Reunião de Kickoff com o cliente realizada
- [ ] Objetivo do projeto compreendido
- [ ] Tecnologias necessárias mapeadas
- [ ] Estimativa de esforço feita
- [ ] Capacidade do time verificada
- [ ] Escopo inicial aprovado pelo cliente

---

## 📤 Checklist de Saída (para encaminhar o projeto às próximas áreas)

- [ ] Documento de Visão preenchido e validado
- [ ] Matriz “é/não é/faz/não faz” definida
- [ ] Wireframes (se aplicável) finalizados
- [ ] Epics e User Stories redigidas
- [ ] Datas de entrada/saída em cada área definidas
- [ ] Contrato e escopo revisados e claros
- [ ] Alinhamento com área de Design ou Desenvolvimento realizado

---

## 📘 Resumo do Projeto

<!-- Explique brevemente o que é o projeto, sua motivação, e o problema que resolve. -->

**Descrição:**
Desenvolver um sistema web para o tatuador Joãozinho Tatuagens, que funcione como cartão de visitas digital e plataforma de gestão. O sistema terá um portfólio organizado por estilos de tatuagem, um módulo de agendamento de sessões com fluxo de aprovação pelo próprio tatuador, além de páginas informativas (FAQ, contato e localização).

**Objetivos:**
- Profissionalizar a presença online do cliente, oferecendo um site organizado e atrativo.
- Facilitar a divulgação do portfólio, permitindo a separação por estilos de tatuagem.
- Automatizar e organizar o processo de solicitação de horários, reduzindo o tempo gasto em conversas informais no WhatsApp e Instagram.
- Criar uma área administrativa intuitiva para o tatuador gerenciar portfólio, agenda e dúvidas frequentes sem necessidade de conhecimentos técnicos.

**Público-Alvo:**
- Clientes em potencial interessados em conhecer os trabalhos do tatuador e solicitar agendamento de sessões.
- O próprio tatuador (administrador do sistema), que utilizará a plataforma para gerenciar seu portfólio, agenda e informações de atendimento.

## 👤 Personas

<!-- 
Liste aqui as personas envolvidas no uso da aplicação. Não é necessário criar nomes fictícios ou descrições elaboradas — o objetivo é identificar os tipos de usuários que interagem com o sistema, suas funções ou necessidades principais.

Exemplos:
- Aluno: acessa o sistema para reservar salas e consultar reservas.
- Funcionário da Biblioteca: administra reservas e atualiza a disponibilidade.
- Professor: visualiza dados de alunos e solicita salas para atividades.
-->

**Principais Funcionalidades:**
- **Portfólio de trabalhos:** Exibição de fotos organizadas por estilo (preto e branco, colorido, fineline etc.).  
- **Galerias categorizadas:** Possibilidade de o cliente compartilhar diretamente links de estilos específicos.  
- **Sistema de agendamento:** Calendário com visualização de horários livres e formulário de solicitação (nome, contato, descrição da tattoo e upload de referência).  
- **Área administrativa:** Painel exclusivo para o tatuador aprovar ou recusar pedidos de agendamento, gerenciar agenda e atualizar portfólio.  
- **Notificações:** Envio de aviso por e-mail (ou outra forma definida) para o tatuador sobre novas solicitações.  
- **FAQ (Perguntas Frequentes):** Página com respostas às dúvidas comuns sobre cuidados, pagamentos e regras.  
- **Página de contato e localização:** Endereço do estúdio, mapa integrado e canais de comunicação.  
- **Gerenciamento simples de conteúdo:** Interface intuitiva para o tatuador adicionar, remover ou editar fotos e informações sem precisar de conhecimento técnico.  

---

## 🧩 Matriz "É / Não É / Faz / Não Faz"
<div align="center">

| Categoria  | Descrição |
|-----------|-----------|
| **É**     | <!-- Ex: Uma aplicação web acessível por desktop e mobile --> |
| **Não É** | <!-- Ex: Um aplicativo nativo para celular --> |
| **Faz**   | <!-- Ex: Permite reservas de salas, equipamentos, exporta relatórios em PDF --> |
| **Não Faz** | <!-- Ex: Controle de acesso físico aos espaços da biblioteca --> |

</div>

---

## 🧠 Matriz de Certezas, Suposições e Dúvidas

<!--
Esta matriz deve ser utilizada para mapear o que já sabemos com segurança (certezas), o que acreditamos mas ainda precisa ser validado (suposições), e o que ainda não sabemos ou precisa ser investigado (dúvidas).

Ela pode ser preenchida em diferentes momentos:
- Logo após a reunião de repasse da área de vendas;
- Durante o processo de elaboração do escopo com o cliente;
- Sempre que surgirem novas informações relevantes.

Essa matriz é útil para orientar as conversas com o cliente, levantar riscos, validar premissas e organizar pontos pendentes.
-->

<div align="center">

| Tipo        | Descrição                                                                |
|-------------|--------------------------------------------------------------------------|
| **Certeza**   | <!-- Ex: O sistema deve ter autenticação via e-mail institucional -->    |
| **Suposição** | <!-- Ex: Acreditamos que o sistema será usado principalmente via mobile --> |
| **Dúvida**    | <!-- Ex: O cliente precisa de integração com sistema acadêmico? -->      |

</div>

---


## 🧱 Epics e User Stories

### 🔹 Epics

<!-- Exemplo: -->
- Epic 1: Gerenciamento de Usuários
- Epic 2: Sistema de Reservas
- Epic 3: Notificações e Alertas
- Epic 4: Relatórios

### 🔸 User Stories

<!-- Exemplo de User Story: -->
#### US1
- **Usuário:** Como um aluno
- **Objetivo:** Quero reservar uma sala de estudo
- **Justificativa:** Para garantir que terei um espaço disponível no horário desejado

<br/>

#### US2
- **Usuário:** Como um professor
- **Objetivo:** Quero ver os alunos da minha turma
- **Justificativa:** Para garantir que consigo acompanhá-los granularmente durante o ano letivo

<!-- Repetir para cada funcionalidade importante -->

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

- RF01 - 
- RF02 - 
- RF03 - 
- RF04 - 

## 📱 Responsividade

**O projeto será responsivo?**
- [ ] Sim
- [ ] Não

**Se sim, até qual ponto?**
- [ ] Mobile-first
- [ ] Adaptável para tablets
- [ ] Desktops Grandes e notebooks menores
- [ ] Totalmente responsivo (desktop, tablet, mobile)

---

## 📌 Observações Finais

<!-- Qualquer observação relevante, como restrições legais, técnicas, dependências externas ou riscos conhecidos. -->

---


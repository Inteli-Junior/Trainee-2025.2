# Desafio do Processo Seletivo - Projeto "Tattoo Studio"

Olá, trainees! Sejam muito bem-vindos ao desafio prático da nossa Área de Projetos.

Nos próximos dias, vocês terão a oportunidade de vivenciar o que fazemos de melhor: transformar a necessidade de um cliente em uma solução tecnológica real e de valor.

## O Cenário

A partir de agora, vocês são a equipe responsável por dar o pontapé inicial em um novo projeto. Um cliente em potencial, um tatuador freelancer, entrou em contato conosco com um problema. Ele não é da área de tecnologia e descreveu sua necessidade de forma informal, como a maioria dos nossos clientes faz.

Este cenário é a nossa rotina. O tempo todo estamos em contato com pessoas não técnicas, e nosso grande diferencial é a habilidade de ouvir, interpretar e traduzir um problema de negócio em uma solução de software coesa e bem planejada.

Este repositório não é apenas para o desafio; ele foi criado a partir do nosso **template padrão para todos os novos projetos** da empresa.

A estrutura de pastas que vocês veem, a documentação com Docusaurus na pasta `/docs` e os documentos que vão preencher são a base de como organizamos e gerenciamos o ciclo de vida de todas as nossas soluções. Portanto, este desafio é uma simulação fiel do primeiro passo de um projeto real conosco. Acostumem-se com esta estrutura, pois ela será sua casa.

## O Ponto de Partida: A Mensagem do Cliente

O único insumo que vocês têm, por enquanto, é a mensagem que o cliente nos enviou. Leiam (ou ouçam) com atenção e tentem se colocar no lugar dele, entendendo suas dores e seus objetivos.

> "E aí, tudo na paz?
> 
> Pô, valeu mesmo por separar um tempo pra me ouvir, cara. A correria tá grande aqui, mas eu precisava muito falar com alguém que entende dessas coisas de... de site, de tecnologia.
> 
> É o seguinte... meu trabalho como tatuador, graças a Deus, tá indo muito bem. Meu Instagram, o @joaozinhotatuagens, tá bombando... o que é ótimo! Mas, sério, tá virando um caos. É uma loucura. A galera me manda DM pra tudo... pra pedir orçamento, pra ver desenho, pra marcar horário... e vira uma bola de neve. Eu me perco todo, juro. Às vezes acho que respondi e não respondi, esqueço de mandar foto de referência, perco o contato da pessoa no meio de outras cinquenta conversas... É uma confusão.
> 
> Aí eu tava pensando... eu precisava de um site. Um 'sitezinho' meu, sabe? Pra ser meu cartão de visitas oficial, uma coisa mais profissional.
> 
> A primeira coisa que eu pensei, o principal mesmo, era um lugar pra eu botar minhas fotos, meu portfólio. Pra ficar organizadinho, sabe? Não aquele feed do Insta que a foto de hoje some amanhã e a pessoa tem que rolar pra sempre pra achar um trabalho antigo. Queria um lugar limpo, só com as fotos das tattoos, pra galera ver a qualidade do meu trampo.
> 
> E... pensando aqui agora... seria animal se desse pra separar, tipo... uma galeria só com os trabalhos em preto e branco, outra com os coloridos, outra com os de fineline... porque a galera sempre me pede 'você tem mais nesse estilo?'. Imagina que foda? Eu só mandaria o link da galeria certa pra pessoa. Ia me poupar um tempo... Nossa, muito tempo.
> 
> Mas... o que tá pegando mesmo, o que tá me tirando o sono, é a agenda. Hoje é um inferno no WhatsApp, sem brincadeira. É um ping-pong infinito:
> 'Tem horário tal dia?'
> 'Esse dia não posso, e na semana que vem?'
> 'E de manhã?'
> 'Ah, de manhã eu trabalho...'
> Cara, eu perco um tempão precioso nisso, tempo que eu podia tá desenhando.
> 
> O meu sonho era ter, tipo... um calendário no site. Onde a pessoa pudesse ver os meus dias e horários livres, de um jeito bem visual. Aí ela clicava lá no horário que ela quer e preenchia um formulário simples... tipo, nome, telefone, e uma descrição básica da ideia da tattoo, talvez até um lugar pra ela mandar uma foto de referência.
> 
> Aí, esse pedido chegaria pra mim. Atenção aqui, ó: não ia marcar o horário direto na agenda, sabe? Porque tatuagem não é assim, eu preciso avaliar o desenho, o tamanho, conversar com a pessoa antes. Mas eu receberia um aviso, sei lá, um e-mail ou uma notificação, e lá no site eu teria um lugar só meu, uma área de administrador, ent> ende? Onde eu pudesse ver todos os pedidos pendentes. E aí eu mesmo ia lá e respondia 'aprovado' ou 'recusado', talvez com uma mensagem. Se eu aprovasse, PÁ! Aquele horário ficava bloqueado na minha agenda pública. Isso seria perfeito!
> 
> Ah! E claro, também precisava de uma página com as dúvidas frequentes. Sabe? 'Como cuidar da tattoo depois?', 'Precisa pagar um sinal?', 'Pode beber antes da sessão?'. Essas coisas que eu respondo umas vinte vezes por dia no WhatsApp. Colocava tudo lá. E o endereço do estúdio com um mapinha, meu contato... o básico, né?
> 
> Enfim... acho que é isso. E pra eu mexer nisso tudo? Pra subir uma foto nova no portfólio, pra bloquear um dia na agenda porque eu vou viajar... tinha que ser super fácil, pelo amor de Deus. Intuitivo. Eu não manjo NADA de programação, meu negócio é com a agulha. Tinha que ser quase tão fácil quanto postar um story, sabe?
> 
> Resumindo o rolê todo: um lugar pra mostrar meu trampo de um jeito profissional, bonito, organizado por estilo... e um sistema pra me ajudar a organizar essa bagunça de agendamento e parar de perder tempo com a parte chata. Quero focar em desenhar e tatuar.
> 
> Cê acha que... que rola fazer algo assim? Dá pra tirar essa ideia do papel?"

## O Desafio: Traduzindo Problemas em Soluções

Vocês perceberão rapidamente que o que o cliente descreve como um "sitezinho" envolve uma complexidade muito maior. Ele vê a ponta do iceberg, mas nós precisamos mapear tudo o que está submerso. Um simples catálogo de imagens e uma agenda exigem:
* Um **frontend** para o cliente final e para o tatuador.
* Um **backend** para gerenciar as regras de negócio (aprovação de agendamentos, upload de fotos, etc.).
* Um (ou mais) **bancos de dados** para armazenar informações estruturadas e arquivos.
* Diferentes **níveis de acesso** (visitante vs. administrador).

**Nosso papel é ser a ponte entre a necessidade do cliente e a solução tecnológica.**

### Atenção aos Detalhes que o Cliente Não Pede

Muitas vezes, funcionalidades essenciais não são mencionadas pelo cliente, pois ele assume que elas simplesmente "existem". Essas tarefas raramente viram requisitos explícitos, mas são cruciais para uma boa experiência do usuário. Cabe a nós, como especialistas, prevê-las.

Por exemplo:
* Toda ação que envolve o servidor (salvar, enviar, apagar) precisa de um feedback visual. O que acontece enquanto a foto está sendo enviada? **Isso é um `loading`**.
* O que acontece quando a ação termina com sucesso ou falha? **Isso é uma `toast message` de sucesso ou erro**.

Pensem em todos os pequenos passos e interações que compõem a experiência completa do produto.

## Seus Entregáveis

Esperamos que vocês, como equipe, entreguem os seguintes artefatos, simulando o fluxo inicial de um projeto em nossa nova estrutura:

1.  **Visão de Produto:** Preencham o documento [`docs/docs/visao-produto.md`](docs/docs/visao-produto.md) (baseado em nosso template oficial). Queremos ver a matriz "é/não é/faz/não faz", os épicos e as principais user stories que vocês identificaram a partir da fala do cliente.

2.  **Design (Wireframe):** Criem um wireframe de baixa fidelidade (rabiscos em papel, Figma, Whimsical, etc.) das principais telas do sistema. Lembrem-se das telas que o cliente não pediu, mas que são necessárias (ex: login, painel administrativo). Anexem as imagens ou o link no documento [`docs/docs/design.md`](docs/docs/design.md). Ele nos revelerá quantas telas o sistema terá, além de quais e quantos níveis de acesso existem.

3.  **Arquitetura Técnica (Modelo de Dados):** Proponham um modelo coneitual para o banco de dados. Quais tabelas seriam necessárias? Como elas se relacionam? Não precisa ser um diagrama complexo, uma descrição textual ou um esquema simples é suficiente. Adicionem essa estrutura no documento [`docs/docs/tecnologias.md`](docs/docs/tecnologias.md).

4.  **Desenvolvimento (Backlog de Tarefas):** Este é um dos entregáveis mais importantes. Utilizando a aba **Projects** deste repositório, criem o backlog inicial do produto. Quebrem os épicos e funcionalidades em tarefas técnicas e acionáveis. Sugerimos usar etiquetas como `frontend`, `backend`, `feature`, `chore`, `bug`.

## Prazo de Entrega

O prazo para a conclusão e apresentação do desafio é de **uma semana** a partir de hoje e finalizando em 12/09.

---

Trabalhem em equipe, organizem-se, discutam, discordem e cheguem a um consenso. Este desafio foi projetado para avaliar não apenas suas habilidades técnicas, mas também sua capacidade de comunicação, colaboração e visão de produto.

Estamos ansiosos para ver a solução que vocês irão construir. Boa sorte!
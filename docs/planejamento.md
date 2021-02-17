# Planejamento

## 1. Cronograma

<p align="jusitfy"> &emsp;&emsp; Ao cronograma das tarefas do projeto foi baseado nas datas de entregas das atividades descritas no plano de ensino da disciplina de Requisitos de Software, visando atender às exigências de cada ponto de controle. É importante ressaltar que as datas podem ser alteradas futuramente, caso seja necessário.

### 1.1 Cronograma das etapas

|Etapas|Título|Data|Descrição|
|-----|------|----|---------|
|I  | Pré-Rastreabilidade            | 11/02-19/02 | Planejamento do Projeto, Rich Picture|
|II |Elicitação de Requisitos        | 20/02-12/03 | Técnicas e Priorização|
|III| Modelagem de Requisitos        | 13/03-22/03 | Cenários , Léxico, Use Case, Especificação Suplementar |
|IV | Modelagem de Requisitos - Ágil | 23/03-01/04 | Histórias de Usuário, Backlogs, NFR Framework|
|V  | Análise de Requisitos          | 02/04-15/04 | Verificação e Validação |
|VI | Pós-Rastreabilidade            | 16/04-03/05 | Gerência de Desenvolvimento de Software orientada à baseline de Requisitos|

## 2. Metodologia

### 2.1 Scrum:

<p align="jusitfy"> &emsp;&emsp; O Scrum é uma metodologia ágil que contém diversas rotinas para manter a equipe engajada e atualizada sobre o projeto, a se organizarem enquanto resolvem um problema e a refletirem sobre os êxitos e fracassos para melhorarem continuamente. Scrum é um framework estrutural usado para gerenciar o desenvolvimento de produtos. Ele é fundado nos princípios de transparência, inspeção e adaptação. Aos princípios do Scrum integramos eventos, papéis e artefatos, administrando as relações e interações entre eles.</p>

![](https://i2.wp.com/www.scrumportugal.pt/wp-content/uploads/como-funciona-o-scrum.png?fit=1300,570)

### 2.2 Kanban:

<p align="jusitfy"> &emsp;&emsp; O Kanban, trata-se de uma simbologia visual usada no desenvolvimento de produtos para registrar o progresso das atividades. Essa metodologia foi criada pela empresa Toyota e integra o famoso sistema Toyota de produção.

<p align="jusitfy"> &emsp;&emsp; O Kanban é orientado através de colunas, em que cada uma representa diferentes estados de completeza de uma atividade (a fazer, fazendo, feito), as atividades (cartões visuais) vão transitando entre as colunas, mostrando o andamento do projeto.</p>

![](https://blog.caelum.com.br/wp-content/uploads/2016/01/kanban.jpg)

### 2.3 Política de Branches

![Git Flow Documentação](../assets/planejamento/GitFlowDocumentation.png)

<p align="jusitfy"> &emsp;&emsp; O Git Flow do repositório de documentação será tratado da forma mostrada na imagem acima. Para uma mudança chegar a branch master (branch estável) os passos abaixo são seguidos:

1. Toda nova branch deve ser feita a partir da master
2. Ao resolver a issue proposta a nova branch deve ser merjada e comparada em relação a master
3. Caso o PR seja aprovado pela equipe a nova branch será deletada e seu conteúdo integrado a master

#### 2.3.1 Regras de Nomenclatura

<p align="jusitfy"> &emsp;&emsp; Toda nova branch criada no repositório do projeto deve se propor a resolver uma issue específica, o nome da branch deve seguir as seguintes regras:

1. Conter o código da issue fornecido pelo GitHub
2. Ser curto e expressivo a respeito da issue a ser tratada
3. As palavras devem ser separadas por um hífen "-"
4. Ser escrito em "lower case"
</p>

Exemplo:

    1-rich-picture

### 2.4 Política de commits:

<p align="jusitfy"> &emsp;&emsp; Os commits devem ser pequenos e para resolver um problema específico. A mensagem do commit deve relatar o que foi feito de maneira sucinta e direta, além disso ela precisa estar em português, começar com um verbo e com a primeira letra maiúscula.

<p align="jusitfy"> &emsp;&emsp; Contribuições feitas por mais de uma pessoa devem conter o comando "Co-authored-by" para identificar todos os autores envolvidos.

Exemplo de contribuição feita por um autor:

    git commit -m "Adiciona documento de planejamento"
    
Exemplo de contribuição feita por mais de um autor:

    git commit -m "Cria Rich Picture
    
    Co-authored-by: Pessoa <emailgit@email.com>"

### 2.5 Política de pull requests:

<p align="jusitfy"> &emsp;&emsp; Para realizar um Pull Request (PR) para o repositório é necessário seguir os passos abaixo.

1. Ao resolver uma issue suba suas contribuições e crie um Pull Request
2. Escreva um título sucinto para o PR
3. Preencha a descrição do PR seguindo os passos e as orientações do template que será mostrado
4. Ligue o PR com a issue que ele resolve
5. Preencha informações adicionais caso possua (executores, revisores, etc)
6. Um PR só poderá ser merjado após duas aprovações.

## 3. Horários disponíveis dos integrantes

<p align="justify"> &emsp;&emsp; A tabela a seguir mostra os horários diários dos integrantes da equipe, visando o melhor aproveitamento do tempo para possíveis reuniões futuras.

![]()

## 4. Ferramentas 

|| Ferramenta | Finalidade |
|---|---|---|
| <img width=120 src="./assets/planejamento/logos/github-logo.png"/>| GitHub | Hospedagem e versionamento de código |
|<img width=120 src="./assets/planejamento/logos/github-pages-logo.png"/>| GitHub Pages | Hospedagem de página web para repositório GitHub |
|<img width=100 src="./assets/planejamento/logos/docker-logo.png"/>| Docker | Ferramenta de isolamento de ambiente |
|<img width=120 src="./assets/planejamento/logos/docker-compose-logo.png"/>| Docker-Compose | Ferramenta de gerenciamento de containers |
|<img width=100 src="./assets/planejamento/logos/zenhub-logo.png"/>|Zenhub| Ferramenta para gerenciamento do kanban no github|
|<img width=100 src="./assets/planejamento/logos/hackmd-logo.png"/>|HackMD| Ferramenta para edição colaborativa de documentos em markdown|
|<img width=80 src="./assets/planejamento/logos/google-meet-logo.png"/>|Google Meet| Ferramenta para reunião online|
|<img width=80 src="./assets/planejamento/logos/drive-logo.png"/>|Google Drive| Ferramenta para compartilhamento de documentos e imagens |
|<img width=80 src="./assets/planejamento/logos/visual-studio-code-logo.svg"/>|VS Code| Ferramenta para edição e adição de documentos|
|<img width=100 src="./assets/planejamento/logos/microsoft-teams-logo.png"/>|Microsoft Teams| Ferramenta para gravação das apresentações da equipe|
|<img width=80 src="./assets/planejamento/logos/telegram-logo.webp"/>|Telegram| Ferramenta para comunicação da equipe|

## 5. Versionamento
			
|Data|Versão|Descrição|Auto|			
|----|------|---------|----|			
|17/02/2021|1.0|Desenvolvimento do documento de planejamento |Lucas Boaventura, Tiago Samuel, Herick Portugues, Ítalo Alves|

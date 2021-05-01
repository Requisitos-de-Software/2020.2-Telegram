# Backlog do Produto

## 1. Introdução

<p align='justify'> &emsp;O backlog de produto em um projeto ágil contém uma lista de demandas de trabalho que um time deve realizar. São normalmente compostos de histórias de usuário, mas alguns times também colocam outros requisitos, processos de negócio, e defeitos a serem corrigidos (Wiegers e Beatty, 2013). Este documento se destina a descrever e priorizar o conjunto de épicos e histórias de usuário que irão compor o escopo de requisitos do aplicativo Telegram.</p>

## 2. Épicos

<p align='justify'> &emsp;Podem ser descritos como grandes áreas do projeto que não foram detalhadas a ponto de se tornarem histórias de usuário e, portanto, não podem ser transformadas em incrementos ou funcionalidades do produto. Nesse projeto os épicos foram separados em:</p>

- [Perfil](ep01_epico_perfil.md) 
- [Contatos](ep02_epico_contatos.md)
- [Chamadas](ep03_epico_chamada.md)
- [Chat](ep04_epico_chat.md)
- [Mensagens](ep05_epico_mensagens.md)
- [Pessoas Próximas](ep06_epico_pessoas_proximas.md)
- [Configurações](ep07_epico_configuracoes.md)
    
## 3. Histórias de Usuário

<p align='justify'> &emsp;Histórias de usuários são, resumidamente, uma forma simplificada de descrever os requisitos que devem ser contemplados no produto final. Essas histórias devem ser descritas de forma natural, num formato que seja possível visualizar como o usuário estabelecerá uma relação com a aplicação por meio de determinada funcionalidade. Nesse documento as histórias planejadas foram separadas por épicos e ao acessar cada épico é possível encontrar os critérios de aceitação de cada história. As histórias foram descritas da seguinte forma:</p>

- Eu, como um usuário, gostaria de < OBJETIVO >, para poder < UMA RAZÃO >

### EP01: Épico Perfil

|  ID | Eu, como usuário gostaria de...             |    Para poder...      |  Prioridade | Rastreabilidade |
| :-: | :-----------------------------------------: | :-------------------: | :--------: | :-------------: |
| US01 | Me cadastrar no aplicativo                  | Ter acesso ao sistema | Must | RF27 |
| US02 | Realizar login no aplicativo                | Utilizar todas as funcionalidades | Must | RF28  |
| US03 | Visualizar meu perfil                       | Acessar minhas informações cadastradas | Must | RF30  |
| US04 | Editar meu perfil           | Alterar informações da minha conta  | Must | RF29 | 
| US05 | Adicionar uma nova conta ao meu dispositivo | Gerenciar diferentes contas no aplicativo | Could | RF18 |
| US06 | Alternar entre contas                       | Utilizar todas as minhas contas cadastradas | Could | RF18 |

### EP02: Épico Contatos

|  ID | Eu, como usuário gostaria de...    |    Para poder...      |  Prioridade | Rastreabilidade |
| :-: | :--------------------------------: | :-------------------: | :---------: | :-------------: |
| US07 | Adicionar novos contatos          | Interagir com eles no aplicativo | Must | RF31 |
| US08 | Visualizar meus contatos          | Verificar os contatos adicionados | Must | RF42  |
| US09 | Visualizar o perfil de um contato | Conferir as informações cadastradas | Should | RF32 |
| US10 | Editar um contato                 | Alterar as informações cadastradas | Must | RF48 |
| US11 | Apagar um contato                 | Retirar da minha lista de contatos | Must | RF49 |
| US12 | Bloquear um contato               | Evitar interação com ele no aplicativo | Must | RF47 |
| US13 | Convidar amigos para o aplicativo | Adicionar ao meus contatos | Should | RF50 |

### EP03: Épico Chamadas

|  ID | Eu, como usuário gostaria de...|    Para poder...      | Prioridade | Rastreabilidade |
| :-: | :-----------------------------: | :--------------------: | :--------: | :-------------: |
| US14| Realizar chamadas de voz individuais   | Conversar por meio de chamada de voz com uma pessoa           |    Should   | RF7 |
| US15| Realizar chamadas de voz em grupo      | Conversar por meio de chamada de voz com mais de uma pessoa   |    Won't    | RF8 |
| US16| Realizar chamadas de vídeo individuais | Conversar por meio de chamada de vídeo com uma pessoa         |    Should   | RF9 |
| US17| Realizar chamadas de vídeo em grupo    | Conversar por meio de chamada de vídeo com mais de uma pessoa |    Won't    | RF10 |

### EP04: Épico Chat
|  ID | Eu, como usuário gostaria de...|              Para poder...                  | Prioridade | Rastreabilidade |
| :-: | :-----------------------------: | :------------------------------------------: | :--------: | :-------------: |
| US18  |   Iniciar uma nova conversa    |    Trocar mensagens com outros usuários     |    Must    | RF38 |
| US19  |        Criar um grupo          |  Trocar mensagens com um grupo de usuários  |    Must    | RF11 |
| US20  |   Criar um novo canal de voz   | Enviar mensagens a diversos usuários de uma só vez |    Must    | RF53 |
| US21  |     Pesquisar mensagens        |       Encontrar mensagens específicas       |  Should    | RF37|
| US22  |      Pesquisar usuários        |       Encontrar usuários do aplicativo      |  Should    | RF42|
| US23  |       Apagar conversas         |             Gerenciar meus chats            |    Must    | RF54|
| US24  |       Fixar conversas          |       Priorizar a visualização de chats     |  Should    | RF55 |
| US25  |      Arquivar conversas        | Ocultar a visualização de chats sem deletar |  Should    | RF56 |

### EP05: Épico Mensagens
|  ID | Eu, como usuário gostaria de...|    Para poder...      | Prioridade | Rastreabilidade |
| :-: | :-----------------------------: | :-------------------: | :--------: | :------------: |
| US26| Enviar/Receber mensagem de texto  | Trocar mensagens de texto          |    Must   | RF1 |
| US27| Enviar/Receber mensagem de áudio  | Trocar mensagens de áudio          |    Must   | RF2 |
| US28| Enviar/Receber arquivos de imagem da galeria | Trocar arquivos de imagem da galeria|    Must    | RF3 |
| US29| Enviar/Receber arquivos de imagem capturados na hora | Trocar arquivos de imagem capturados na hora |  Could   | RF4 |
| US30| Enviar/Receber arquivos de vídeo da galeria | Trocar arquivos de vídeo da galeria |    Must    | RF5 |
| US31| Enviar/Receber arquivos de vídeo gravados na hora | Trocar arquivos de vídeo gravados na hora|    Could    | RF6 |
| US32| Criar grupos de mensagens | Trocar mensagens em grupo |    Must    | RF11 |
| US33| Criar enquetes | Realizar enquetes|    Could    | RF12 |
| US34| Salvar mensagens | Visualizar determinada mensagem depois |    Could   | RF13 |
| US35| Encaminhar mensagens | Espelhar mensagem sem precisar copiá-la |    Should    | RF14 |
| US36| Excluir mensagens enviadas | Apagá-la em caso de arrependimento |    Should    | RF15 |
| US37| Enviar/Receber arquivos | Trocar arquivos |    Must   | RF16 |
| US38| Responder uma mensagem enviada num grupo no privado da pessoa que a enviou| Responde-la com mais privacidade | Could| RF33 |
| US39| Salvar e visualizar as mensagens salvas de uma conversa em específico | Visualizá-la depois de forma mais fácil |    Won't    | RF34 |
| US40| Enviar/Receber uma música | Trocar músicas |    Could    | RF44 |

### EP06: Épico Pessoas Próximas

|  ID | Eu, como usuário gostaria de...    |    Para poder...      |  Prioridade | Rastreabilidade |
| :-: | :--------------------------------: | :-------------------: | :---------: | :-------------: |
| US41 | Encontrar pessoas próximas a mim            | Interagir com elas no aplicativo | Could | RF26 |
| US42 | Ficar visível para usuários próximos | Ser encontrado por eles no aplicativo | Could | RF51 |
| US43 | Encontrar grupos locais próximos a mim   | Participar de um grupo com pessoas da minha região | Could | RF52  |
| US44 | Criar um grupo local | Ter meu grupo encontrado por pessoas próximas | Could | RF52 |


### EP07: Épico Configurações
|  ID |           Eu, como usuário gostaria de...             |    Para poder...      | Prioridade | Rastreabilidade |
| :-: | :---------------------------------------------------:  | :-------------------:  | :--------: | :-----: |
| US45  |          Acessar minhas mensagens salvas              | Visualizar mensagens específicas |    Could    | RF34 |
| US46  |       Alterar a visualização da aba de chamadas       | Visualizar ou ocultar meu registro de chamadas |    Must    | RF57|
| US47  | Iniciar ou terminar uma sessão em outros dispositivos | Controlar o acesso à minha conta |    Must    | RF18 |
| US48  |                  Criar pastas de chat                 | Organizar minhas conversas |    Could    | RF24 |
| US49  |          Editar e reorganizar pastas de chat          | Controlar a disposição das pastas de conversas |    Could    | RF24|
| US50  | Redefinir ou alterar as configurações de notificações | Configurar a ativação de notificações |   Should    | RF45 |
| US51  |  Alterar as configurações de privacidade e segurança  | Configurar caracteŕisticas importantes para a segurança da minha conta |    Should    | RF58|
| US52  |   Alterar as configurações de dados e armazenamento   | Gerenciar de forma individual meu uso de dados |    Should    | RF59 |
| US53  |         Alterar as configurações de aparência         | Adequar a aparência da aplicação de acordo com meu gosto |    Could    | RF60 |
| US54  |      Alterar o idioma de exibição do aplicativo       | Ter a possibilidade de testar outros idiomas na aplicação |    Must    | RF61 |
| US55  |         Editar e gerenciar pacotes de stickers        | Gerenciar ou remover pacotes de stickers |    Could    | RF62 |

## 4. Referências Bibliográficas
- WIEGERS, Karl; BEATTY, Joy. "Software Requirements". Microsoft Press, 2013.

## 5. Versionamento

| Data       | Versão |                Descrição                                |        Autor(es)        |
| :--------: | :----: | :-----------------------------------------------------: | :---------------------: |
| 30/03/2021 |   1.0  |                  Criação do documento                   |Brenda, Herick e Lorrany |
| 01/04/2021 |   1.1  |         Adição dos épicos chat e configurações          |         Brenda          |
| 01/04/2021 |   1.2  |         Adição dos épicos mensagens e chamadas          |         Lorrany         |
| 01/04/2021 |   1.3  |  Adição dos épicos perfil, contatos e pessoas próximas  |    Hérick Portugues     |
| 01/04/2021 |   1.4  |            Revisão e correções no documento             |Brenda, Herick e Lorrany |
| 02/04/2021 |   1.5  |            Revisa o documento e corrigi referências e formatação           |Lucas Boaventura |
| 27/04/2021 |   1.6  |            Revisa o documento |Tiago Samuel Rodrigues |

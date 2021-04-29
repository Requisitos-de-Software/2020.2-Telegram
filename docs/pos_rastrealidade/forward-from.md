# Forward-From

## 1. Introdução

<p align="justify">&emsp; Nessa etapa de Pós-rastreabilidade chamada Forward-From é onde ligamos os requisitos a artefatos de desenho e implementação. Para essa parte nós optamos por utilizar o meta-modelo de Toranzo.</p>

## 2. Legenda

### 2.1. Classificação da Categoria

<ul>
  <li>
    <p align="justify">
      <strong>Ambiental:</strong> congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido;
    </p>
  </li>
  <li>
    <p align="justify">
      <strong>Organizacional:</strong> reune informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema;
    </p>
  </li>

  <li>
    <p align="justify">
      <strong>Gerencial:</strong> agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto;
    </p>
  </li>

  <li>
    <p align="justify">
      <strong>Desenvolvimento, Gerencial:</strong> abarca informações relacionadas aos diversos artefatos gerados no processo de Desenvolvimento, Gerencial;
    </p>
  </li>

</ul>

## 3. Requisitos Funcionais

| Número do Requisito |                                            Requisito                                            |              Cenários              |        Léxico         | História de Usuário | Categoria                  |
| :-----------------: | :---------------------------------------------------------------------------------------------: | :--------------------------------: | :-------------------: | :-----------------: | :------------------------- |
|         RF1         |                     O usuário deve poder enviar/receber mensagens de texto                      |             Cenário 01             |  L6 - Nova Mensagem   |        US26         | Desenvolvimento, Gerencial |
|         RF2         |                     O usuário deve poder enviar/receber mensagens de áudio                      |             Cenário 02             |  L6 - Nova Mensagem   |        US27         | Desenvolvimento, Gerencial |
|         RF3         |                O usuário deve poder enviar/receber arquivos de imagem da galeria                |             Cenário 03             |  L6 - Nova Mensagem   |        US28         | Desenvolvimento, Gerencial |
|         RF4         |            O usuário deve poder enviar/receber arquivos de imagem capturados na hora            |             Cenário 04             |  L6 - Nova Mensagem   |        US29         | Desenvolvimento, Gerencial |
|         RF5         |                O usuário deve poder enviar/receber arquivos de vídeo da galeria                 |             Cenário 05             |  L6 - Nova Mensagem   |        US30         | Desenvolvimento, Gerencial |
|         RF6         |             O usuário deve poder enviar/receber arquivos de vídeo gravados na hora              |             Cenário 06             |  L6 - Nova Mensagem   |        US31         | Desenvolvimento, Gerencial |
|         RF7         |                    O usuário deve poder realizar chamadas de voz individuais                    |             Cenário 07             |           -           |        US14         | Desenvolvimento, Gerencial |
|         RF8         |                     O usuário deve poder realizar chamadas de voz em grupo                      |             Cenário 08             |           -           |        US15         | Desenvolvimento, Gerencial |
|         RF9         |                   O usuário deve poder realizar chamadas de vídeo individuais                   |             Cenário 09             |           -           |        US16         | Desenvolvimento, Gerencial |
|        RF10         |                    O usuário deve poder realizar chamadas de vídeo em grupo                     |             Cenário 10             |           -           |        US17         | Desenvolvimento, Gerencial |
|        RF11         |                         O usuário deve poder criar grupos de mensagens                          |             Cenário 11             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF12         |                               O usuário deve poder criar enquetes                               |             Cenário 12             |           -           |        US33         | Desenvolvimento, Gerencial |
|        RF13         |                              O usuário deve poder salvar mensagens                              |             Cenário 13             | L1 - Mensagens Salvas |        US34         | Desenvolvimento, Gerencial |
|        RF14         |                            O usuário deve poder encaminhar mensagens                            |             Cenário 14             |           -           |        US35         | Desenvolvimento, Gerencial |
|        RF15         |                         O usuário deve poder excluir mensagens enviadas                         |             Cenário 15             |           -           |        US36         | Desenvolvimento, Gerencial |
|        RF16         |                          O usuário deve poder enviar/receber arquivos                           |             Cenário 16             |           -           |        US37         | Desenvolvimento, Gerencial |
|        RF17         |                   O sistema deve permitir a utilização e configuração de bots                   |             Cenário 17             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF18         |          O sistema deve permitir a alternância de contas por meio do mesmo dispositivo          |             Cenário 18             |   L3 - Dispositivos   |        US06         | Desenvolvimento, Gerencial |
|        RF19         | O sistema deve permitir o controle da frequência de mensagens que podem ser enviadas nos grupos |             Cenário 19             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF20         |            O usuário deve conseguir ver a confirmação de uma mensagem lida em grupos            |             Cenário 20             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF21         |            O usuário deve poder bloquear o acesso ao aplicativo por meio da digital             |             Cenário 21             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF22         |    O usuário deve poder gerenciar o armazenamento interno ocupado por uma conversa ou grupo     |             Cenário 22             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF23         |         O sistema deve manter o histórico de mensagens do grupo para novos integrantes          |             Cenário 23             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF24         |                      O sistema deve permitir a divisão dos chats em pastas                      |             Cenário 24             |  L4 - Pastas de Chat  |          -          | Desenvolvimento, Gerencial |
|        RF25         |                 O sistema deve manter os arquivos e mensagens salvos na "nuvem"                 |             Cenário 25             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF26         |         O usuário deve poder encontrar pessoas próximas à ele que utilizam o aplicativo         |             Cenário 26             |           -           |          -          | Desenvolvimento, Gerencial |
|        RF27         |                     O usuário deve poder realizar o cadastro no aplicativo                      |             Cenário 27             |           -           |        US01         | Desenvolvimento, Gerencial |
|        RF28         |                       O usuário deve poder realizar o login no aplicativo                       |             Cenário 28             |           -           |        US02         | Desenvolvimento, Gerencial |
|        RF29         |                             O usuário deve poder editar seu perfil                              |             Cenário 29             |           -           |        US04         | Desenvolvimento, Gerencial |
|        RF30         |                           O usuário deve poder visualizar seu perfil                            |             Cenário 30             |           -           |        US03         | Desenvolvimento, Gerencial |
|        RF31         |                          O usuário deve poder adicionar novos contatos                          |             Cenário 31             |           -           |        US07         | Desenvolvimento, Gerencial |
|RF32|O usuário deve poder visualizar o perfil de seus contatos|Cenário 32|-|US09|Desenvolvimento e Gerencial|
|RF33|O usuário deve poder responder uma mensagem enviada num grupo no privado da pessoa que a enviou|Cenário 33|L6 - Nova mensagem|US38|Desenvolvimento e Gerencial|
|RF34|O usuário deve poder salvar e visualizar as mensagens salvas de uma conversa em específico|Cenário 34|-|US39, US34|Desenvolvimento e Gerencial|
|RF35|O usuário deve poder compartilhar sua localização|Cenário 35|-|-|Desenvolvimento e Gerencial|
|RF36|O usuário deve poder visualizar suas conversas existentes|Cenário 36|L8 - Visualização|-|Desenvolvimento e Gerencial|
|RF37|O usuário deve poder acessar conversas existentes|Cenário 37|-|US45|Desenvolvimento e Gerencial|
|RF38|O usuário deve poder criar uma nova conversa|Cenário 38|L6 - Nova Mensagem|US18|Desenvolvimento e Gerencial|
|RF39|O usuário deve poder criar um chat secreto|Cenário 39|L10 - Chat Secreto|-|Desenvolvimento e Gerencial|
|RF40|O usuário deve poder visualizar contatos online|Cenário 40|-|US08|Desenvolvimento e Gerencial|
|RF41|O usuário deve poder procurar contatos|Cenário 41|-|-|Desenvolvimento e Gerencial|
|RF42|O usuário deve poder visualizar e ordenar todos os contatos|Cenário 42|-|US09|Desenvolvimento e Gerencial|
|RF43|O usuário deve poder compartilhar um contato|Cenário 43|-|US07|Desenvolvimento e Gerencial|
|RF44|O usuário deve poder enviar/receber uma música|Cenário 44|-|US44|Desenvolvimento e Gerencial|
|RF45|O usuário deve poder desativar notificações do contato|Cenário 45|-|US50|Desenvolvimento e Gerencial|
|RF46|O usuário deve poder ver grupos que possui em comum com um contato|Cenário 46|-|-|Desenvolvimento e Gerencial|
|RF47|O usuário deve poder bloquear um contato|Cenário 47|L12 - Bloquear|US12|Desenvolvimento e Gerencial|
|RF48|O usuário deve poder editar um contato |Cenário 48|-|US10|Desenvolvimento e Gerencial|
|RF49|O usuário deve poder apagar um contato|Cenário 49|-|US11|Desenvolvimento e Gerencial|
|RF50|O usuário deve poder convidar amigos para o aplicativo|-|-|US13|Desenvolvimento e Gerencial|
|RF51|O usuário deve poder ficar visível para pessoas próximas|-|-|US42|Desenvolvimento e Gerencial|
|RF52|O usuário deve poder criar/participar de grupos locais|-|L2 - Novo Grupo |US43, US44|Desenvolvimento e Gerencial|
|RF53|O usuário deve poder criar canais de voz locais|-|L5 - Novo Canal|US20|Desenvolvimento e Gerencial|
|RF54|O usuário deve poder apagar conversas|-|-|US23|Desenvolvimento e Gerencial|
|RF55|O usuário deve poder fixar conversas locais|-|-|US24|Desenvolvimento e Gerencial|
|RF56|O usuário deve poder arquivar conversas locais|-|-|US25|Desenvolvimento e Gerencial|
|RF57|O usuário deve poder alterar a visualização da aba de chamadas|-|-|US46|Desenvolvimento e Gerencial|
|RF58|O usuário deve poder alterar as configurações de privacidade e segurança|-|-|US51|Desenvolvimento e Gerencial|
|RF59|O usuário deve poder alterar as configurações de dados e armazenamento|-|-|US52|Desenvolvimento e Gerencial|
|RF60|O usuário deve poder alterar as configurações de aparência|-|-|US53|Desenvolvimento e Gerencial|
|RF61|O usuário deve poder alterar o idioma de exibição do aplicativo|-|-|US54|Desenvolvimento e Gerencial|
|RF62|O usuário deve poder editar e gerenciar pacotes de stickers|-|-|US55|Desenvolvimento e Gerencial|

## 4. Referências Bibliográficas

- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 26;
- Sayão, M., & do Prado Leite, J. C. S. (2006). Rastreabilidade de requisitos. RITA, 13(1), 57-86. Toranzo, M., Castro, J., & Mello, E. (2002, November). Uma Proposta para Melhorar o Rastreamento de Requisitos. In WER (pp. 194-209).

## 5. Versionamento

| Data       | Versão | Descrição                   | Autor                            |
| ---------- | ------ | --------------------------- | -------------------------------- |
| 27/04/2021 | 0.1    | Cria estrutura do documento | Brenda Santos e Lucas Boaventura |
| 28/04/2021 | 0.2    | Detalha do RF1 ao RF31 | Brenda Santos |
| 29/04/2021 | 1.0    |  Detalha do RF32 ao RF62 |Lucas Boaventura |

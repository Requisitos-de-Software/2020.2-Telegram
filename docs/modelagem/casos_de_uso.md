# Casos de Uso

## Introdução
<p align='justify'> &emsp;Um caso de uso tem como função descrever como um ator/usuário realizará uma tarefa no sistema. Ele descreve, pelo ponto de vista do usuário, o comportamento do sistema conforme ele vai respondendo às solicitações. Cada caso de uso é representado como uma sequência de etapas simples, que começa com um objetivo/meta do usuário e termina quando este é concluido. Essas etapas são definidas a partir de um Diagrama de Casos de Uso, seguido pelas especificações dos casos, em que se é possível observar uma breve descrição e um fluxo de utilização do caso.</p>

## Casos de Uso

#### UC01 - Enviar Mensagem
![UC01](../assets/modelagem/uc01_mensagens.png)
<figcaption>Figura 1. Imagem que ilustra o Casos de Uso ao enviar mensagem.</figcaption>

|   UC01   |  Informações  |
| ----------------- | ------- |
| Descrição | O usuário envia uma mensagem |
| Ator | Usuário |
| Pré-condições | Acesso à internet e estar logado no app |
| Ação | O usuário envia uma mensagem para outro usuário |
| Fluxo Principal | **FP01:** Fluxo de enviar mensagem para um usuário que o ator já interagiu </br> 1. O ator entra no aplicativo </br> 2. O sistema exibe uma lista de conversas recentes </br> 3. O ator procura pelo usuário que deseja conversar </br> 4. O ator clica sobre o chat desse usuário </br> 5. O ator digita/seleciona um dos diferentes tipos de mensagens </br> 6. O ator clica no botão de enviar |
| Fluxo Alternativo | **FA01:** Fluxo de enviar mensagem para um novo usuário </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão flutuante no canto inferior direito </br> 3. O sistema exibe a lista de contatos </br> 4. O ator procura pelo contato que deseja iniciar uma conversa </br> 5. O ator clica sobre o contato desse usuário </br> 6. O ator digita/seleciona um dos diferentes tipos de mensagens </br> 7. O ator clica no botão de enviar |
| Pós-condições | O ator poderá utilizar os chats com seus contatos |
| Rastreabilidade | Requisitos Funcionais 1-6, 13-16, 35-38, 43-44 do [documento final de elicitação](https://requisitos-de-software.github.io/2020.2-Telegram/elicitacao/Resultado_e_Prioriza%C3%A7%C3%A3o/resultado/) |

#### UC02 - Criar/Participar de Grupo
![UC01](../assets/modelagem/uc02_grupos.png)
<figcaption>Figura 1. Imagem que ilustra o Casos de Uso ao criar/participar de umgrupo.</figcaption>

|   UC01   |  Informações  |
| ----------------- | ------- |
| Descrição | O usuário cria ou participa de um grupo |
| Ator | Usuário |
| Pré-condições | Acesso à internet e estar logado no app |
| Ação | O usuário cria/participa de um grupo |
| Fluxo Principal | **FP01:** Fluxo de criar um grupo de mensagens pela tela principal </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão flutuante no canto inferior direito </br> 3. O sistema exibe uma lista de opções </br> 4. O ator clica sobre a opção "Criar Grupo" </br> 5. O ator seleciona os contatos que deseja adicionar ao grupo </br> 6. O ator adiciona um nome e uma imagem ao grupo </br> 7. O ator clica no botão inferior direito para criar o grupo </br> 8. O ator pode realizar as diversas funções relacionadas ao grupo |
| Fluxo Alternativo | **FP01:** Fluxo de criar um grupo pela menu lateral </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo </br> 3. O sistema abre o menu lateral </br> 4. O ator clica sobre a opção "Criar Grupo" </br> 5. O ator seleciona os contatos que deseja adicionar ao grupo </br> 6. O ator adiciona um nome e uma imagem ao grupo </br> 7. O ator clica no botão inferior direito para criar o grupo </br> 8. O ator pode realizar as diversas funções relacionadas ao grupo |
| Pós-condições | O ator terá um grupo de mensagens criado |
| Rastreabilidade | Requisitos Funcionais 11-12 do [documento final de elicitação](https://requisitos-de-software.github.io/2020.2-Telegram/elicitacao/Resultado_e_Prioriza%C3%A7%C3%A3o/resultado/) |

#### UC03 - Configurações
![UC01](../assets/modelagem/uc03_configuracoes.png)
<figcaption>Figura 1. Imagem que ilustra o Casos de Uso ao acessar as configurações do aplicativo.</figcaption>

|   UC01   |  Informações  |
| ----------------- | ------- |
| Descrição | O usuário configura o aplicativo |
| Ator | Usuário |
| Pré-condições | Estar logado no app |
| Ação | O usuário edita as configurações do aplicativo |
| Fluxo Principal | **FP01:** Fluxo de editar o perfil </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo  </br> 3. O sistema abre o menu lateral </br> 4. O ator clica na opção de "Configurações" </br> 5. O sistema lista as opções de configuração </br> 6. O ator seleciona uma opção da primeira seção (Conta) </br> 7. O ator altera uma informação do seu perfil |
| Fluxo Alternativo | **FP01:** Fluxo de editar outras configurações do app </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo  </br> 3. O sistema abre o menu lateral </br> 4. O ator clica na opção de "Configurações" </br> 5. O sistema lista as opções de configuração </br> 6. O ator seleciona uma opção da segunda seção (Configurações) </br> 7. O ator configura uma informação relacionada ao aplicativo |
| Pós-condições | O ator terá suas configurações atualizadas |
| Rastreabilidade | Requisitos Funcionais 22, 29 do [documento final de elicitação](https://requisitos-de-software.github.io/2020.2-Telegram/elicitacao/Resultado_e_Prioriza%C3%A7%C3%A3o/resultado/) |

#### UC04 - Visualizar Pessoas Próximas
![UC01](../assets/modelagem/uc04_pessoas_proximas.png)
<figcaption>Figura 1. Imagem que ilustra o Casos de Uso ao visualizar pessoas próximas.</figcaption>

|   UC01   |  Informações  |
| ----------------- | ------- |
| Descrição | O usuário visualiza pessoas próximas a ele no aplicativo |
| Ator | Usuário |
| Pré-condições | Acesso à internet e estar logado no app |
| Ação | O usuário encontra pessoas próximas a ele |
| Fluxo Principal | **FP01:** Fluxo encontrar usuários próximos e iniciar um conversa </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo  </br> 3. O sistema abre o menu lateral </br> 4. O ator clica na opção de "Pessoas Próximas" </br> 5. O sistema lista na primeira seção uma lista de pessoas próximas ao ator </br> 6. O ator clica sobre um usuário </br> 7. O ator clica no botão de enviar uma mensagem para o usuário |
| Fluxo Alternativo | **FP01:** Fluxo de tornar-se visível para outros usuários </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo  </br> 3. O sistema abre o menu lateral </br> 4. clica na opção de "Pessoas Próximas" </br> 5. O ator clica sobre a opção de "Ficar Visível" </br> </br> **FP02:** Fluxo de participar de um grupo local </br> 1. O ator entra no aplicativo </br> 2. O ator clica no botão superior esquerdo  </br> 3. O sistema abre o menu lateral </br> 4. clica na opção de "Pessoas Próximas" </br> 5. O ator navega até a seção "Grupos Próximos" </br> 6. O ator clica sobre um grupo local que deseja participar </br> 7. O sistema exibirá o grupo selecionado </br> 8. O usuário clica no botão inferior "Entrar" e começa a participar do grupo |
| Pós-condições | O ator encontrará pessoas e grupos próximos a ele |
| Rastreabilidade | Requisito Funcional 26 do [documento final de elicitação](https://requisitos-de-software.github.io/2020.2-Telegram/elicitacao/Resultado_e_Prioriza%C3%A7%C3%A3o/resultado/) |

## Bibliografia
- Use Cases. usability.gov. Disponível em: https://www.usability.gov/how-to-and-tools/methods/use-cases.html. Acesso em: 22 de mar. de 2021.

## Versionamento
|   Data     | Versão |        Descrição             |     Autor(es)    |
| :--------: | :----: | :--------------------------: | :--------------: |
| 24/03/2021 |  0.1   | Criação dos Casos de Uso     | Hérick Portugues |
| 25/03/2021 |  1.0   | Desenvolvimento do documento | Hérick Portugues |
| 25/03/2021 |  2.0   | Revisão do documento e adição de descrição das imagens | Lucas Boaventura |
# Léxicos
## 1. Introdução
<p align='justify'> &emsp;O processo de criação de requisitos de um sistema pode ser dividido em três grandes atividades: Elicitação, modelagem e análise. Ao longo da etapa de elicitação, a concepção do produto e de seus domínios são diretamente influenciada pelos clientes, usuários e diversos outros profissionais de diferentes áreas, tornando assim mais fácil a ocorrência da utilização de termos técnicos e expressões específicas que podem facilmente ser interpretadas de formas diferentes pelos leitores. A criação de léxico tem como principal objetivo a necessidade de que todos os participantes do processo de desenvolvimento do produto compartilhem da mesma compreensão sobre os termos próprios da aplicação, e, além de ser uma exigêcia de processos de qualidade, servem também de fonte de consulta para os participantes envolvidos na engenharia de requisitos. O método utilizado para a identificação de símbolos para o léxico é dirigida ao <strong>Léxico Ampliado da Linguagem (LAL)</strong>, onde cada símbolo é descrito com noção(o que significa o símbolo), impacto(descrição de efeito dos símbolos na aplicação ou vice-versa) e um tipo(verbo, objeto ou estado). Sendo assim, os léxicos serão padronizados com a utilização da tabela abaixo:</p>

|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto/Estado/Verbo|Denotação|Conotação| Opcional  |

## 2. Léxicos 
#### L1 - **Mensagens Salvas**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| ----------------- | ------- | ------- | --------- |
|Objeto|Uma lista de diversas mensagens, de conversas que podem ou não ser diferentes|O ator encaminha as mensagens que deseja salvar ao chat "mensagens salvas", visando encontrá-las mais facilmente quando necessário|  -  |

#### L2 - **Novo Grupo**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Opção que permite a criação de um novo grupo de conversas|Possibilita a criação do grupo, a escolha de um ícone, a escolha do nome e dos conatos que se tornarão membros| - |

#### L3 - **Dispositivos**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Lista os dispositivos aos quais a conta está vinculada|Mostra os dispositivos utilizados para acessar a conta, permitindo desconectar-se de um ou todos a qualquer momento|Máquinas, aparelhagem|

#### L4 - **Pastas de Chat**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Cria pastas de chat|Permite a organização de diversos chats em pastas, permitindo a alternância rápida dentre os chats| - |

#### L5 - **Novo Canal**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Cria um novo canal de mensagens|Permite a criação de um novo canal onde os contatos incluidos poderão receber mensagens como em uma lista de transmissão|  -  |

#### L6 - **Nova Mensagem**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Permite a seleção de um contato que deverá receber a mensagem|O contato será selecionado e será possível enviar mensagens de texto, de voz, arquivos, gifs etc.| - |

#### L7 - **Nome de Usuário**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Nome de usuário escolhido pelo dono da conta|Permite a criação de um nome de usuário(único) que pode ser utilizado para encontrar e contatar o usuário sem precisar de seu contato salvo| *Username*  |

#### L8 - **Visualização**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Mostra a ultima vez que o usuário ficou online no aplicativo|Torna visível se o usuário está online, viu as mensagens recentemente, viu as mensagens no ultimo mês etc.| Status, visto por último |

#### L9 - **API Bot**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|API que suporta a criação de bots|Permite que bots sejam facilmente criados e chamados em chats/grupos de conversas, auxiliado pelo *BotFather*| - |

#### L10 - **Chat Secreto**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Objeto|Funcionalidade que permite iniciar um chat secreto com outro usuário|Cria o chat secreto, que possui mensagens autodestrutivas, bloqueio de encaminhamento e criptografia de ponta a ponta, proporcionando uma privacidade maior aos usuários| - |

#### L11 - **Encaminhar**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Verbo|Ato relacionado ao encaminhamento de mensagens a grupos ou usuários|O usuário recebe a mensagem encaminhada e pode visualizar de quem a mensagem foi encaminhada, sua origem| Reenviar, redirecionar |

#### L12 - **Bloquear**
|   Classificação   |  Noção  | Impacto | Sinônimos |
| :---------------: | :-----: | :-----: | :-------: |
|Verbo|Ação relacionada com o bloqueio de uma conta por um usuário|O usuário não poderá mais receber mensagens d contato que foi bloqueado| Ignorar, privar-se |

## 3. Referências Bibliográfica
- SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;
- SAYÃO, Miriam; DE CARVALHO, Gustavo R. Construção do léxico de aplicações.

## 4. Versionamento
|   Data     | Versão |              Descrição                 |   Autor(es)   |
| :--------: | :----: | :------------------------------------: | :-----------: |
| 21/03/2021 |  1.0   | Criação e desenvolvimento do documento | Brenda Santos |
| 22/03/2021 |  1.1   | Revisa e formata documento | Lucas Boaventura |
| 27/04/2021 |  1.2   | Revisão do Documento | Tiago Samuel |
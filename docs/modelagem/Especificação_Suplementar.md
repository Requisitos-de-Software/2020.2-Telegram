# Especificação Suplementar

## 1. Introdução

<p align='justify'>&emsp; A especificação suplementar aborda os requisitos funcionais e principalmente os não funcionais do sistema, basicamente se aliando com outras técnicas de requisitos como a modelagem e a elicitação possibilitando ter uma margem mais robusta de alcançar os requisitos do sistema. Nesse contexto nós temos os atributos de qualidade do sistema, os requisitos de usabilidade, segurança, desempenho e suportabilidade, além de outros requisitos, como requisitos de compatibilidade, restrições de design, sistemas operacionais e ambientes.
 </p>

### 1.1. Finalidade

<p align='justify'>&emsp; Esse documento visa descrever requisitos não funcionais do Telegram. Entende-se por requisito não funcional todo aquele requisito que especifica critérios que podem ser usados para julgar a operação de um sistema, ao invés de comportamentos específicos.</p>

### 1.2. Escopo

<p align='justify'>&emsp; O telegram é um aplicativo para troca de mensagens entre usuários. Existem vários tipos de mensagens dentro do aplicativo e também é possível realizar chamadas e alguns outros requisitos. </p>

## 1.3 Metodologia

<p align='justify'> &emsp; A metodologia utilizada será o método FURPS+, que é um modelo para classificação de atributos de qualidade de software.</p>

- F - Funcionality (Funcionalidade)<br/>
  Especifica as funcionalidades que não se relacionam com os casos de uso, nomeadamente: auditoria, reporte, interoperabilidade e segurança.

- U - Usability (Usabilidade)<br/>
  Avalia a interface com o utilizador. Possui diversas subcategorias, entre elas: prevenção de erros, estética e design, documentação, consistência e padrões.

- R - Reliability (Confiabilidade)<br/>
  Refere-se à integridade, conformidade e interoperabilidade do software. Os requisitos a serem considerados são: frequência e gravidade de falhas, possibilidade de recuperação, extensão e duração da falha (valorização/sobrevivência) e previsibilidade (estabilidade).

- P - Performance (Performance)<br/>
  Avalia os requisitos de desempenho do software nomeadamente: tempo de resposta, consumo de recursos (energia, RAM, CPU, cache, etc), capacidade e escalabilidade.

- S - Suportability (Suportabilidade)<br/>
  Os requisitos de suportabilidade agrupam várias características, tais como: testabilidade, adaptabilidade, manutenabilidade, campatibilidade, configurabilidade, instalabilidade, escalabilidade, entre outros.

- Restrições de Design/Acessibilidade <br/>
  Especifica ou restringe o processo de design do sistema. Exemplos podem incluir:

  - Padrões de Design;
  - Processo de Desenvolvimento de Software;
  - Uso de Ferramentas de Desenvolvimento;
  - Biblioteca de Classes; etc.

- Requisitos de Implementação <br/>
  Especifica ou restringe o código ou a construção de um sistema, através de restrições comoː

  - Limites de Recursos;
  - Sistema Operativos; etc.

- Requisitos de Interface <br/>
  Especifica ou restringe as funcionalidades inerentes às interfaces de diferentes componentes. A utilização de módulos externos é comum e as restrições a ela associada devem ser contempladas nesta secção.
- Requisitos Físicos <br/>
  Especifica uma restrição física imposta pelo hardware usado para implantar o sistema.

## 2. Requisitos Não Funcionais

<p align='justify'> &emsp; Os requisitos não funcionais são aqueles que não estão descritos na seção de elicitção de requisitos.</p>

### 2.1. Funcionalidade

<p align='justify'> &emsp; O requisitos funcionais do aplicativo Telegram estão descritos em sua maioria na seção de <a href="">casos de uso</a>.</p>

### 2.2. Usabilidade

- <p align='justify'>O Telegram deve possuir ferramentas de edição de fotos e vídeos poderosas, stickers e emojis animados, temas completamente personalizáveis e uma plataforma de GIFs/stickers para fornecer toda expressão que o usuário precisar.</p>

- <p align='justify'>O aplicativo deve possuir uma interface limpa que seja tão simples que o usuário já saiba como usar.</p>

### 2.3. Confiabilidade

- <p align='justify'>O aplicativo deve providenciar a melhor segurança combinada com o uso fácil.

- <p align='justify'>Tudo no Telegram incluindo conversas, grupos, mídias, etc deve ser fortemente criptografado utilizando a combinação simétrica AES de 256-bits, RSA 2048-bits e a troca de chaves seguras Diffie-Heelman.</p>

- <p align='justify'>O aplicativo deverá permitir a exclusão, para ambos os lados, de qualquer mensagem a qualquer momento e sem rastros por parte dos usuários.</p>

- <p align='justify'>O Telegram não utilizará os dados dos usuários para mostrar anúncios.</p>

### 2.4. Performance

- <p align='justify'>O aplicativo deve funcionar até nas conexões móveis mais instáveis.</p>

- <p align='justify'>O aplicativo deve ser o mensageiro mais rápido do mercado, conectando as pessoas através de diversos servidores ao redor do mundo.</p>

- <p align='justify'>O sistema deve estar disponível 24h por dia.</p>

- <p align='justify'>O aplicativo deve entregar as mensagens utilizando a menor quantidade de bytes possíveis.</p>

- <p align='justify'>O aplicativo deve permitir a criação de grupos com até 200 mil membros, a compartilhação de forma rápida de vídeos grandes, documentos de qualquer tipos de até 2GB cada, e definir bots para tarefas específicas utilizando a API.</p>

- <p align='justify'>O aplicativo deve permitir o envio de mídias e arquivos sem qualquer limites de tamanho ou tipo. O histórico de conversas não precisará ocupar espaço em disco do dispositivo e deverá ser armazenado de forma segura na nuvem por quanto tempo o usuário precisar.</p>

### 2.5. Suportabilidade

- <p align='justify'>O usuário deve poder acessar as suas mensagens de todos os seus celulares, tablets e computadores ao mesmo tempo independente do navegador utilizado.</p>

- <p align='justify'>O aplicativo deve ser independente e permitir que o usuário não mantenha o celular conectado.</p>

- <p align='justify'>O Telegram deve possuir uma API completamente gratuita e documentada para desenvolvedores.</p>

### 2.6. Restrições de Design

- <p align='justify'>O aplicativo deve ter um design de alta compreensão e acessibilidade.</p>

### 2.7. Requisitos de Implementação

- <p align='justify'>O aplicativo deverá possuir um código fonte aberto e builds verificáveis para provar que o app baixado foi construído usando exatamente o mesmo código fonte que é publicado.</p>

### 2.8. Requisitos de Interface/Acessibilidade

<p align='justify'> &emsp; Para os requisitos de interface e acessibilidade acessibilidade do aplicativo Telegram, terá como base a cartilha da W3C, que conta com os seguintes pontos:</p>

- <p align='justify'>Cores e contraste: o app deve possuir requisitos específicos para a personalização completa das cores no aplicativo, permitindo ser acessível a qualquer pessoa.</p>

- <p align='justify'>O aplicativo deve possuir ícones intuitivos e de fácil visualização para todos usuários e dispositivos.</p>

- <p align='justify'>O aplicativo deverá ter botões bem claros e com boa área de resposta ao clique/touch.</p>

- <p align='justify'>O aplicativo deve possuir alternativas aos elementos sonoros.</p>

- <p align='justify'>O aplicativo deve conter sugestões visuais que garatam as informações das páginas ao usuário.</p>

- <p align='justify'>O aplicatido deve conter textos descritivos e bem dispostos na tela para melhor leitura dos usuários.</p>

- <p align='justify'>O aplicativo deve conter clareza nos links mostrados na tela ao usuário.</p>

### 2.9. Requisitos Físicos

- <p align='justify'>O espaço físico utilizado pelo Telegram deve ser o menor possível dentro de seu limite.</p>

# Referências Bibliográficas

- BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.

- Página [Sobre o App](https://play.google.com/store/apps/details?id=org.telegram.messenger&hl=pt_BR&gl=US) do aplicativo Telegram na Play Store.

- [Recomendações de Acessibilidade para Conteúdo Web (W3CAG)](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/)

## Versionamento

| Data       | Versão | Descrição                                                 | Autor                           |
| ---------- | ------ | --------------------------------------------------------- | ------------------------------- |
| 21.03.2021 | 1.0    | Desenvolvimento do documento de especificação suplementar | Lucas Boaventura e Tiago Samuel |
| 30.03.2021 | 2.0    | Arruma numeração dos tópicos do documento                 | Lucas Boaventura                |
| 30.04.2021 | 2.1    | Revisão do documento                                      | Ítalo Alves                     |

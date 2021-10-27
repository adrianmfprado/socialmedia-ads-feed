# projeto do Módulo 02 - React

projeto para encerramento do módulo 02, aplicando os conhecimentos obtidos sobre o React e sua estrutura.

## instruções

objetivo: construir uma aplicação SPA com React que busque uma lista de publicidades de uma rede social em uma api pública e construa na página através de componentes um widget que exiba os anúncios em forma de feed, mostrando seu conteúdo, e suas interações (curtidas, compartilhamentos e comentários).


 - construir o layout do componente seguindo o modelo do figma ([disponível aqui](https://www.figma.com/file/HFLKG8ZtLaQSuJFJv2Ii7M/Facebook-Ads-Post?node-id=0%3A1))
 - utilizar a biblioteca axios ([disponível aqui](https://www.npmjs.com/package/axios)) para buscar e pegar os dados na api através de requisições http
 - utilizar o endereço da api pública pre-selecionada ```https://api.npoint.io/144c46739f80c9eeb6b7``` ([disponível aqui](https://api.npoint.io/144c46739f80c9eeb6b7))


## página principal & feed

na construção da página da aplicação, fica a cargo do aluno pensar e desenvolver uma página que simule uma rede social (criar um header, footer, e outros elementos de uma rede social fake), encaixando o componente responsável pelo feed em algum lugar da página da aplicação.

## detalhes

o que mais será avaliado será a preocupação com os detalhes. pensar em soluções para os pequenos detalhes dos componentes utilizando as ferramentas e o ciclo de vida dos componentes do React. alguns detalhes para se atentar (por exemplo):

 - enquanto estiver carregando dados da api, exibir uma mensagem ou um ícone de "carregando..."
 - tratar o conteúdo dos posts e dos comentários para identificar links e hashtags automáticamente
 - quando clicar no botão de curtir, compartilhar, ou comentar, simular as ações do componente
 - ao escrever um comentário, adicioná-lo junto à lista de comentários do post
 - ao clicar na imagem, abrir um lightbox para exibi-la maior
 - exibir ícone de "verificado" quando necessário

## extras

serão consideradas como "pontos extras" as seguintes situações:

  - identificar e aplicar o uso de hooks customizados
  - uso devido/correto de bibliotecas de terceiros
  - organização/separação adequada dos componentes e suas pastas


## entrega

a entrega deve ser feita pelo classroom, como já de costume, lá deve ser registrado o link do repositório público do git contendo a aplicação desenvolvida.


## considerações finais

o maior intuito deste projeto é fornecer um caso de uso próximo da realidade do mercado (consumo de apis e atividades e exercícios de lógica como de uma rede social) para que dentro desse contexto seja possível explorar a criatividade e a capacidade de pensar e desenvolver soluções para os problemas apresentados.

fico à disposição para esclarecer qualquer dúvida.

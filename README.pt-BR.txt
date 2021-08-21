<p align="center">
  <img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/avs/docs/ux/branding/mark1._TTH_.png">
  <br/>
  <h1 align="center">Kit SDK da Alexa Skills para Node.js</h1>
</p>

*[English](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/blob/2.0.x/README.md) | [日本語](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/blob/2.0.x/README.ja.md) | [Português do Brasil](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/blob/2.0.x/README.pt-BR.md)*

O **ASK SDK v2 para Node.js** facilita construir skills com alto engajamento permitindo você gastar menos tempo implementando funcionalidades, além de garantir uma melhor legibilidade de código.

O [**ASK SDK Controls Framework (Beta)**](https://github.com/alexa/ask-sdk-controls) construído no ASK SDK v2 para Node.js, provêm uma solução escalável para grandes criações, usando multiplos turnos com componentes reusáveis chamados de *controls*.

O **ASK SMAPI SDK for Node.js** fornece aos desenvolvedores uma biblioteca de fácil comunicação com todas as "Skill Management APIs (SMAPI)", incluindo "interaction model", histórico de "intent request", e "in-skill purchasing APIs".

## Versões de Pacote

| Pacote         | NPM            |
| ------------- | ------------- |
|[ask-sdk](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk)| [![npm](https://img.shields.io/npm/v/ask-sdk.svg)](https://www.npmjs.com/package/ask-sdk) [![npm](https://img.shields.io/npm/dt/ask-sdk.svg)](https://www.npmjs.com/package/ask-sdk)|
|[ask-sdk-core](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-core)| [![npm](https://img.shields.io/npm/v/ask-sdk-core.svg)](https://www.npmjs.com/package/ask-sdk-core) [![npm](https://img.shields.io/npm/dt/ask-sdk-core.svg)](https://www.npmjs.com/package/ask-sdk-core)|
|[ask-sdk-dynamodb-persistence-adapter](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-dynamodb-persistence-adapter)| [![npm](https://img.shields.io/npm/v/ask-sdk-dynamodb-persistence-adapter.svg)](https://www.npmjs.com/package/ask-sdk-dynamodb-persistence-adapter) [![npm](https://img.shields.io/npm/dt/ask-sdk-dynamodb-persistence-adapter.svg)](https://www.npmjs.com/package/ask-sdk-dynamodb-persistence-adapter)|
|[ask-sdk-runtime](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-runtime)| [![npm](https://img.shields.io/npm/v/ask-sdk-runtime.svg)](https://www.npmjs.com/package/ask-sdk-runtime) [![npm](https://img.shields.io/npm/dt/ask-sdk-runtime.svg)](https://www.npmjs.com/package/ask-sdk-runtime)|
|[ask-sdk-s3-persistence-adapter](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-s3-persistence-adapter)| [![npm](https://img.shields.io/npm/v/ask-sdk-s3-persistence-adapter.svg)](https://www.npmjs.com/package/ask-sdk-s3-persistence-adapter) [![npm](https://img.shields.io/npm/dt/ask-sdk-s3-persistence-adapter.svg)](https://www.npmjs.com/package/ask-sdk-s3-persistence-adapter)|
|[ask-sdk-v1adapter](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-v1adapter)|[![npm](https://img.shields.io/npm/v/ask-sdk-v1adapter.svg)](https://www.npmjs.com/package/ask-sdk-v1adapter) [![npm](https://img.shields.io/npm/dt/ask-sdk-v1adapter.svg)](https://www.npmjs.com/package/ask-sdk-v1adapter)|
|[ask-sdk-express-adapter](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-express-adapter)|[![npm](https://img.shields.io/npm/v/ask-sdk-express-adapter.svg)](https://www.npmjs.com/package/ask-sdk-express-adapter) [![npm](https://img.shields.io/npm/dt/ask-sdk-express-adapter.svg)](https://www.npmjs.com/package/ask-sdk-express-adapter)|
|[ask-smapi-sdk](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-smapi-sdk)| [![npm](https://img.shields.io/npm/v/ask-smapi-sdk.svg)](https://www.npmjs.com/package/ask-smapi-sdk) [![npm](https://img.shields.io/npm/dt/ask-smapi-sdk.svg)](https://www.npmjs.com/package/ask-smapi-sdk)|
|[ask-sdk-local-debug](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-local-debug)| [![npm](https://img.shields.io/npm/v/ask-sdk-local-debug.svg)](https://www.npmjs.com/package/ask-sdk-local-debug) [![npm](https://img.shields.io/npm/dt/ask-sdk-local-debug.svg)](https://www.npmjs.com/package/ask-sdk-local-debug)|

## Funcionalidades da Alexa suportadas pelo SDK

- [Amazon Pay](https://developer.amazon.com/docs/amazon-pay/integrate-skill-with-amazon-pay.html)
- [Audio Player](https://developer.amazon.com/docs/custom-skills/audioplayer-interface-reference.html)
- [Display – Body templates for devices with a screen](https://developer.amazon.com/docs/custom-skills/create-skills-for-alexa-enabled-devices-with-a-screen.html)
- [Gadgets Game Engine – Echo Buttons](https://developer.amazon.com/docs/custom-skills/game-engine-interface-reference.html)
- [Directive Service (Progressive Response)](https://developer.amazon.com/docs/custom-skills/send-the-user-a-progressive-response.html)
- [Messaging](https://developer.amazon.com/docs/smapi/send-a-message-request-to-a-skill.html)
- [Monetization](https://developer.amazon.com/alexa-skills-kit/make-money)
- [Video](https://developer.amazon.com/docs/custom-skills/videoapp-interface-reference.html)
- [Device Address](https://developer.amazon.com/docs/custom-skills/device-address-api.html)
- [Lists](https://developer.amazon.com/docs/custom-skills/access-the-alexa-shopping-and-to-do-lists.html#alexa-lists-access)
- [Request for customer contact information](https://developer.amazon.com/docs/alexa/custom-skills/request-customer-contact-information-for-use-in-your-skill.html)
- [Obtain customer settings information](https://developer.amazon.com/docs/smapi/alexa-settings-api-reference.html)
- [Account Linking](https://developer.amazon.com/docs/account-linking/understand-account-linking.html)
- [Entity Resolution](https://developer.amazon.com/docs/custom-skills/define-synonyms-and-ids-for-slot-type-values-entity-resolution.html)
- [Dialog Management](https://developer.amazon.com/docs/custom-skills/dialog-interface-reference.html)
- [Location Services](https://developer.amazon.com/docs/custom-skills/location-services-for-alexa-skills.html)
- [Reminders](https://developer.amazon.com/docs/smapi/alexa-reminders-overview.html)

### Funcionalidades em fase de teste

As seguintes funcionalidades são lançamentos em fase de teste pública. As interfaces talvez possam mudar nos futuros lançamentos.

- [Connections](https://developer.amazon.com/blogs/alexa/post/7b332b32-893e-4cad-be07-a5877efcbbb4/skill-connections-preview-now-skills-can-work-together-to-help-customers-get-more-done)
- [Alexa Presentation Language](https://developer.amazon.com/docs/alexa-presentation-language/apl-overview.html)
- [Name-free Interactions](https://developer.amazon.com/docs/custom-skills/understand-name-free-interaction-for-custom-skills.html)

## Documentação Técnica

- [English](https://developer.amazon.com/docs/alexa-skills-kit-sdk-for-nodejs/overview.html)
- [日本語](https://ask-sdk-for-nodejs.readthedocs.io/ja/latest/)

## Modelos

O SDK usa um modelo de classes em vez de requisições/respostas em esquemas JSON da [documentação dos desenvolvedores](https://developer.amazon.com/docs/custom-skills/request-and-response-json-reference.html). O código fonte para o modelo de classes pode ser encontrado [aqui](https://github.com/alexa/alexa-apis-for-nodejs).

## Exemplos

### [Hello World](https://github.com/alexa/skill-sample-nodejs-hello-world)
Amostra para familiarizar você com o Kit da Alexa Skill e AWS Lambda permitindo você ouvir uma resposta da Alexa quando você acionar a skill.

### [Hello World (Controls framework)](https://github.com/alexa/skill-sample-controls-hello-world)
Amostra para familiarizar você com a Framework Controls, permitindo você ouvir uma resposta da Alexa quando você acionar a skill.

### [Fact](https://github.com/alexa/skill-sample-nodejs-fact)
Template para basic fact skill. Você irá prover uma lista de fatos interessantes sobre um determinado assunto, a Alexa irá selecionar o fato randomicamente e dizer para o usuário quando a skill for invocada.

### [How To](https://github.com/alexa/skill-sample-nodejs-howto)
Template para skill baseada em parâmetros chamada 'Minecraft Helper'. Quando o usuário pergunta como construir um item no jogo Minecraft, a skill irá prover as instruções.

### [Trivia](https://github.com/alexa/skill-sample-nodejs-trivia)
Template para jogo de pergunta e respostas com gravação de placar. A Alexa irá fazer uma pergunta de multipla escolha e pedirá a resposta. Respostas corretas e incorretas são gravadas.

### [Quiz Game](https://github.com/alexa/skill-sample-nodejs-quiz-game)
Template para um simples jogo de quiz. A alexa irá perguntar sobre fatos que você fornecer.  

### [City Guide](https://github.com/alexa/skill-sample-nodejs-city-guide)
Template para skill de recomendações no local. Alexa usa os dados que você prover para oferecer recomendações de acordo com as preferências do usuário.

### [Pet Match](https://github.com/alexa/skill-sample-nodejs-petmatch)
Skill de Demonstração que recomenda um animal de estimação para o usuário. Alexa pergunta ao usuário por informações necessárias para a recomendação. Uma vez que toda as informações forem coletadas, a skill envia os dados para um serviço externo que processa os dados e retorna a recomendação.

### [High Low Game](https://github.com/alexa/skill-sample-nodejs-highlowgame)
Template para um jogo básico de menor-maior. Quando o usuário advinha um numero, Alexa diz se o numero é maior ou menor que o numero que ela tem em mente.

### [Decision Tree](https://github.com/alexa/skill-sample-nodejs-decision-tree)
Template para skill básica de teste vocacional. Alexa pergunta ao usuário uma série de questões para uma sugestão de carreira.

### [Fruit Shop (Controls framework)](https://github.com/alexa/skill-sample-controls-fruit-shop)
Constrói uma skill muti-modal para loja de compras de frutas usando customização e uma biblioteca que controla os itens da lista, gerencimaneto carrinho de compra, e pagamento.

### [Device Address API](https://github.com/alexa/skill-sample-node-device-address-api)
Skill de amostra que mostra como pedir e acessar um endereço configurado no dispositivo do usuário.

### [Audio Player](https://github.com/alexa/skill-sample-nodejs-audio-player)
Projeto que mostra como usar o audio player para skills.

## Kit SDK da Alexa Skills em outras linguagens
<a href="https://github.com/alexa/alexa-skills-kit-sdk-for-java"><img src="https://github.com/konpa/devicon/raw/master/icons/java/java-original.svg?sanitize=true" width="25px" /> Kit SDK da Alexa Skills para Java</a>

<a href="https://github.com/alexa/alexa-skills-kit-sdk-for-python"><img src="https://github.com/konpa/devicon/blob/master/icons/python/python-original.svg?sanitize=true" width="25px" /> Kit SDK da Alexa Skills para Python</a>

## Teve uma nova ideia?
Requisite e vote por novas funcionalidades da alexa [aqui](https://alexa.uservoice.com/forums/906892-alexa-skills-developer-voice-and-vote/filters/top?category_id=322783)!

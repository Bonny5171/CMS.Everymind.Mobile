# CMS.Everymind.Mobile

Aplicação React Native aplicando arquitetura offline first no React Native. Para testes, recomendo que você instale essas dependências com o auxílio do gerenciador de pacotes para Windows, Chocolatey ou qualquer um de sua preferncia ou OS.
Duvidas so me contatar luis.city@gmail.com

Características
* Renderização condicional offline / online através de técnicas de HOC ou Render Callback
* Reducer para manter seu estado de conectividade na loja Redux
* Redux middleware para interceptar ações de requisição de internet no modo offline e aplicar o princípio DRY
* Compatibilidade com bibliotecas de middleware assíncronas como redux-thunk, redux-saga e redux-observable
* Saga para colocar as inscrições de evento de rede fora de seus componentes
* Um passo além do NetInfo detectando acesso à Internet além de conectividade de rede
* Suporte à fila offline para reenviar ações automaticamente quando a conexão estiver on-line novamente ou descartar ações com base em outras ações enviadas (ou seja, relacionadas à navegação)
* Capacidade de verificar a conectividade regularmente

## Iniciando

Essas instruções farão com que você tenha uma cópia do projeto em execução na sua máquina local para fins de desenvolvimento e teste. Veja a implantação de notas sobre como implantar o projeto em um sistema ativo.

### Prerequisites

* Node js - Versão instalada é a 4 ou mais recente.
* python2 
* jdk8
* React Native

### Preparando ambiente

Para realização de testes na aplicação, foi utilizado um "Android Studio" e para IOS o proprio emulador para IOS.

```
choco install -y nodejs.install python2 jdk8
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

## Running the tests

Explain how to run the automated tests for this system

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Node](https://nodejs.org/en/)
* [React-native](https://facebook.github.io/react-native/docs/getting-started.html)
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds
* [Netinfo](https://facebook.github.io/react-native/docs/netinfo.html) API do NetInfo que define status de conectividade ON/OFF-LINE

## Authors

* **Luis Fernando** - *Initial work* - [Bonny5171](https://github.com/Bonny5171)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Gradecimentos

* Everymind pela iniciativa do projeto.
* Offline first: como funciona e como aplicar no React Native? [link](https://blog.rocketseat.com.br/offline-first-react-native/)

## JSDay-Offline-first-the-painless-way-wide
https://d2yei5s1by8ykd.cloudfront.net/wp-content/uploads/2015/05/22111227/jSDay-Offline-first-the-painless-way-wide.001-800x450.jpg

## Montagem de um ambiente para desenvolvimento.

Tentei emular para IOS porem não tenho mac.
Tentei emular no meu OS Windows 10 porem como tenho PC AMD sem virtualização VT VX da intel não consigo utilizar um emulador do android.
Estou partindo para 3 opção o app Expo, que sera utilizado para disponibilizar o app para Tester, amigos eu stakeholders.

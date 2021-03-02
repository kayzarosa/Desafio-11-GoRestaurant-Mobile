<h1 align="center">
    <img alt="Rocketseat GoStack" src="https://camo.githubusercontent.com/d25397e9df01fe7882dcc1cbc96bdf052ffd7d0c/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732e706e67" width="100%" />
</h1>

## Rocketseat

# :rocket: Desafio 11: GoRestaurant - Mobile

> <img src="https://user-images.githubusercontent.com/20192309/80269274-a0373880-8684-11ea-9a84-73519e476030.jpg" width="5%" /> Sorria sempre independente do que esteja acontecendo, pois tudo passa.

## Sobre o desafio

Neste desafio criamos um app para a venda e entrega de comida via delivery, temos a busca o menu de categoria e a lista de itens, também apresentamos no menu a lista de pedidos e a listagem de itens favoritos do cliente.

## Versão

````sh
NodeJS 12.16.2
Yarn 1.22.4
React 16.11.0
React-Native 0.62.1
Watchman 4.9.0
````


## Instalação

````sh
yarn
````

## Banco de dados

Aqui usamos o json-sever que nos fornece os dados que o aplicativo irá consumir, o comando abaixo inicia o servidor.

````sh
yarn json-server --host 192.168.0.8 -p 3333 --watch server.json
````

## Executar a aplicação

Antes de tudo o seu ambiente deve estar configurado de acordo com o link abaixo: 

<a href="https://react-native.rocketseat.dev/"> Roketseat </a>

Após as configurações feitas pra executar o aplicativo no emulador ou no celular executar os seguintes comandos:

Para sistemas android:

````sh
react-native run-android

ou

yarn android

````
Para sistemas iOS:

````sh
react-native run-ios

ou

yarn ios

````

O processo pode demorar um pouco, ao terminar se nenhum terminal abrir para monitorar as alterações realizada executar o seguinte comando:


````sh
react-native start

ou

yarn start

````

## A aplicação

Segue abaixo uma demonstração do que foi feito.


![MobileGoRestaurante](https://user-images.githubusercontent.com/20192309/109689925-90ba3300-7b64-11eb-8c80-1a48c0370a80.gif)
 

Feito com ♥ by Kayza :wave:

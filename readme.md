# Portal Academico da Faculdade

Projeto em React Native com Expo para um mini portal academico com foco no aluno.

## Tecnologias

- React Native
- Expo
- JavaScript

## Funcionalidades

- Entrada de dois numeros (`Valor A` e `Valor B`)
- Botao para calcular a soma
- Exibicao do resultado na tela
- Cor do resultado:
	- Verde para resultado positivo ou zero
	- Vermelho para resultado negativo

## Como rodar o projeto

1. Instale as dependencias na raiz do repositorio:

```bash
npm install
```

2. Inicie o app do aluno (encaminhado para `portal-aluno`):

```bash
npm start
```

3. Execute no ambiente desejado:

```bash
npm run android
npm run ios
npm run web
```

## Estrutura basica

```text
.
|- package.json
|- portal-aluno/
|  |- App.js
|  |- index.js
|  |- app.json
|  |- package.json
|  |- src/
|  |  |- components/
|  |  |  |- DrawerContent.js
|  |  |- data/
|  |  |  |- dados.js
|  |  |- screens/
|  |     |- BuscaScreen.js
|  |     |- FeedScreen.js
|  |     |- PublicacaoScreen.js
```

## Observacoes

- Os comandos da raiz usam `npm --prefix portal-aluno` para executar o app principal.
- Para abrir no celular, use o app Expo Go e escaneie o QR code exibido no terminal.

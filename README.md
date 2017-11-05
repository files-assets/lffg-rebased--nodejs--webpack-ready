# Webpack Ready

Uma aplicação simples que roda com _Webpack_, _Babel_ e _React_.  
Conta com diversos _loaders_ para o _Webpack_, como:
* _PostCSS_;
* _SASS_;
* _Babel_;
* E outros...

### Ambiente de Desenvolvimento

Para configurar o ambiente de desenvolvimento do _Webpack_, basta alterar o booleano na primeira linha do `webpack.config.js`.

Para um ambiente de desenvolvimento:
```js
const production = false;
```

Para um ambiente de produção:
```js
const production = true;
```

# Scripts

Iniciar o _webpack-dev-server_:
```shell
npm start
```

Gerar o _bundle.js_:
```shell
npm run build
```

Fazer com que o _webpack_ observe (_watch_) os arquivos:
```shell
npm run watch
```

### Licença

Este repositório e todo seu conteúdo está sob a [Licença MIT](https://github.com/lffg/webpack-ready/blob/master/LICENSE).

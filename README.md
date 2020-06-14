# Deploy ReactJS

- Mais detalhes em [Deployment](https://create-react-app.dev/docs/deployment)

- Uma das soluções gratuitas que podemos utilizar já com integração com o github é o [netlify](https://www.netlify.com)

- Criar conta ou se logar

- Clicar em `New site from Git`

- Escolher o repositório

- Escolher o branch

- Clicar em `Deploy Site`

- Aguardar finalizar o deploy

- Para visualizar o site podemos clicar em `Preview`

- No menu deploy nessa página aparecerá a url de produção

- Para adicionar um dominio próprio podemos ir em `Settings > Domain management`

- Clica em `Add custom domain` em segue o as instruções

- O HTTPS precisa adicionaro dominio e pode ser configuarada nessa página de `Settings`

- Algo que precisamos fazer é configurar o controle de rotas conforme [deployment#netlify](https://create-react-app.dev/docs/deployment#netlify)

  - Criar o arquivo `public/_redirects`:

  ```js
    /*  /index.html  200
  ```

  - Salvar o arquivo commit e push

- Dessa forma o netlify já iniciará um novo deploy automático

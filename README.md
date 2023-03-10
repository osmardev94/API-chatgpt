# API-chatgpt

# 🚀 Tecnologias:

Nesse projeto foram utilizadas as seguintes tecnologias:

### ⚛️ Tecnologias principais

- [Node.js](https://nodejs.org/en/)
- [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

### 📚 Libs & Dependências

- [openAI](https://npmjs.com/package/openai) - Para integrar com algoritmos openAI
- [express](https://.npmjs.com/package/express) - Para criar api rest
- [cors](https://.npmjs.com/package/cors) - Controle de acesso
- [dotenv](https://.npmjs.com/package/dotenv) - Configurações de arquivos
- [nodemon](https://.npmjs.com/package/nodemon) - Monitoramento do server node

### 🥷 Arquitetura

- [N-Tier Architecture](https://www.baeldung.com/cs/n-tier-architecture)

## :information_source: Como utilizar

Para executar este aplicativo, você precisará de [Git](https://git-scm.com), [Node.js v14.16](https://nodejs.org/en/) ou superior + [ NPM v8](https://nodejs.org/en/) ou superior instalado em seu computador.
Executar os comandos:

# Instalar dependências
$ npm install

# Rodar (development ambient)
$ npm run dev
```
* A biblioteca precisa ser configurada com a chave secreta da sua conta, que está disponível ao se cadastrar site "https://platform.openai.com/overview". 
Configure a chave de API como uma variável de ambiente em .env. Em seguida utilize o método POST em json com a linha "prompt:"

# Aplicação Backend na linguagem TypeScript


# Definição

Aplicação back-end usando typescript, com banco de dados usando a biblioteca prisma, aplicada no Postman e com a criação de um OAuth Apps no GitHub. Com a possibilidade de se conectar com o OAuth liberando um code ('/github' - GET), trazer algumas informações do usuário e a liberação do token a partir do code ('/authenticate - POST'), criar várias mensagem para o seu usuário com o requerimento do token ('/messages' - POST), listar as últimas 3 mensagens que foram enviadas ('/messages/last3' - GET) e listar algumas informações do usuário com o requerimento do token ('/profile' - GET). 

Obs: Também é possível ver dentro do banco de dados com o prisma.

# Dependências usadas

- Prisma: Automatização ao acesso ao banco de dados;
- Axios: Cliente HTTP baseado em Promises para fazer requisições;
- Cors: Mecanismo que usa cabeçalhos adicionais HTTP para informar a um navegador que permita que um aplicativo Web seja executado em uma origem (domínio) com permissão para acessar recursos selecionados;
- Dotenv: Orquestrar as variáveis ambiente de um projeto;
- Express: Popular framework, escrito em JavaScript, que roda sobre o ambiente NodeJS em tempo de execução. Configura o seu ambiente de desenvolvimento e executa tarefas comuns de desenvolvimento e implantação da web.
- Jsonwebtoken: Sistema gerador de senhas que vários bancos usam para garantir a segurança do cliente e evitar fraudes.
- Socket.io:  Oferece uma API de JavaScript simples, baseada em eventos que te permite comunicar entre o servidor e o cliente sem esforço e em tempo real.

# Comandos

Para configuração
```bash
npm install 
```

Para rodar a aplicação
```bash
npm start
```

Rodando no http://localhost:4000

Para acesso ao banco de dados pelo prisma
```bash
npx prisma studio
```

# Resultado

Conectar o GitHub e pegar o code:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563007-de68958d-a665-4434-bb71-c98ec5cfbe6f.gif", width=900>
</span>

Autenticar o code:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563211-897780dd-e090-4916-bda7-ad48a3693da3.gif", width=900>
</span>

Criar uma mensagem:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563061-43eefc25-d360-4eb3-84d4-872c4d469759.gif", width=900>
</span>

Listar as 3 últimas mensagens:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563076-314e4173-fd67-49f0-b0d6-accd666a24c1.gif", width=900>
</span>

Visualizar informações do usuário:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563040-3403da99-4eb3-4506-ae00-f0b528cd0866.gif", width=900>
</span>

Acesso ao banco de dados pelo prisma:

<span>
      <img src="https://user-images.githubusercontent.com/85804895/139563368-b15b037a-aee8-4fa0-b07c-8a06bed4ea32.gif", width=900>
</span>

# Agradecimentos

NWL Heat Rockseat 🚀🚀🚀




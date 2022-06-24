<h1 align="center">
    <a href="https://github.com/Fernanda1701/blog"> Blog✨ </a>
</h1>
<p align="center">Desenvolvendo um blog com as tecnologias de Nodemailer, Json Server e Angular</p>

<h2 align="center">
<img src="https://img.shields.io/static/v1?label=Status:&message=Completo ✅&color=32CD32&style=for-the-badge&logo=ghost"/>
</h2>


## 💎 Sobre

O projeto tem como objetivo a criação de um blog que possui um gerenciamento de dados de mensagens (feito com Json Server), envio de email (feito com Nodemailer) e um frontend (feito em Angular). As operações de gerenciamento de mensagens possuem:

- Id
- Nome
- Mensagem

<p>E podemos efetuar as seguintes requisições:</p> 

- [x] Cadastro
- [x] Leitura 
- [x] Atualização  
- [x] Remoção

<p>Já no email temos:</p>

- Nome
- Email
- Mensagem

<p>Para que houvesse um bom funcionamento foram criadas as APIs de backend de <b>email</b> e <b>banco de dados</b>, pelas quais são consumidas pelo <b>frontend</b>, pautando-se na arquitetura de microsserviços.</p>

## ⚙️ Execução

 Para o carregamento do site, iniciaremos o angular. Abra o terminal, vá para a pasta frontend e digite o seguinte comando:

```bash
npm install
```
Após a instalação, digite:
```bash
ng serve
```
Executando o comando acima, abra o seguinte endereço:
```bash
http://localhost:4200
```
Para startar o db, abra o terminal e vá para a pasta db e digite o seguinte comando:
```bash
npm start
```
Assim o Json Server estará disponível para uso no seguinte endereço:
```bash
http://localhost:3000
```

<p>Para startar o Nodemailer é preciso adicionar um email e senha válidos, que irão receber os emails enviados pelo blog, no aquivo <a href="https://github.com/Fernanda1701/blog/blob/master/backend/email/details.json">details.json</a>.</p> 
Feito isso, no terminal, entre na pasta email e digite o seguinte comando:

```bash
node app.js
```

Ele abrirá na porta:

```bash
http://localhost:3001
```
Após tudo inicializado podemos cadastrar mensagens no feed, pesquisa-las por nome do remetente e enviar emails no contato. Na porta 3000 podemos fazer cadastro, leitura, atualização e remoção de mensagens.

## 🛠 Tecnologias
 
- [Angular](https://angular.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [Json Server](https://www.npmjs.com/package/json-server)
- [Bootstrap](https://getbootstrap.com/)
- [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [TypeScript](https://www.typescriptlang.org/)
- Versionamento de código no [Git](https://git-scm.com/)


## 💻 IDE

- [IntelliJ](https://www.jetbrains.com/pt-br/idea/)
- [VScode](https://code.visualstudio.com/)


## 🧐 OBS

Veja a versão desse código implementado em <a href="https://github.com/Fernanda1701/java-nodemailer-angular-blog">Java, Nodemailer, Angular e H2</a>.


## Autor:

<a href="https://github.com/Fernanda1701">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/Fernanda1701" width="80px;" alt=""/>
 <br />
 <sub><b>Fernanda Nascimento</b></sub></a> <a href="https://github.com/Fernanda1701"></a>

Entre em contato ✉️:

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda-blue??style=plastic&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fnasci/)](https://www.linkedin.com/in/fnasci/)
[![Gmail Badge](https://img.shields.io/badge/-fnasci.1701@gmail.com-c14438?style=plastic&logo=Gmail&logoColor=white&link=mailto:fnasci.1701@gmail.com)](mailto:fnasci.1701@gmail.com)

# MANUAL DE DESENVOLVIMENTO WEB UTILIZANDO O SITE VERCEL


by Fernando Tunouti


---

Este manual é um compilado de comandos inspirado no vídeo de Filipe Deschamps entitulado *Sites Modernos*  https://youtu.be/EW7m2WIvFgQ , último acesso em 14/03/2023.


---
1. Utilizando o Framework NEXT.JS -  criado pela Vercel
 * configurando um ambiente de desenvolvimento, de forma que se possa realisar Deploy tanto de Testes como de Produção;
 * primeiro criar repositório no gitHub , marcar a opção Add.gitgnore para *template:Node*, clique em *Create Repository*
 * após criado o repositório copie o link dele e clone na sua máquina local com git clone...
 * abrir a pasta e utilizar o comando *code .* para abrir o VsCode
 * abrir um novo Terminal no VsCode
 * a partir deste momento você precisa ter na máquina o Node.Js no mínimo na versão 10.3 que é a menor versão compatícel com o Next 10
 * iniciar o projeto criando um arquivo package.json com o comando:
    > npm init -y , a opção *y* serve para aceitar todas as opções padrão 
 * criar a dependência do Next.Js, React  e React.DOM com o comando:
    > npm install next react react-dom
 *  Rodar o framework localmente e cria uma página estática 
    > primeiramente, modificar o arquivo *package.json*  criando um atalho para o React.DOM, acrescentando a linha (dev: "next dev") na linha *scripts; ver imagem vercel1.png
 * agora, toda vez que queremos subir o servidor do Next.Js localmente para desenvolver basta rodar o comando:
    > npm run dev , onde dev é o nome do script que inserimos em package.json
 * inicialmente haverá uma mensagem de erro, por isso, será necessário realizar o seguinte:
    > criar uma pasta *pages* no projeto, e dentro dela criar um arquivo *index.js* , pode ser também um arquivo *index.ts*, caso queira trabalhar com typescript
 * dentro do arquivo index criar uma função Home() conforme imagem : vercel2.png
 * acrescentar no arquivo também a linha , para que o framework possa entender qual o componente/função representa a nossa página:
    > export default Home , este é o novo padrão de módulos do JS que exporta por padrão o componente que queremos que seja renderizado como página -- ver imagem verce3.png
 * salve tudo e rode o comando:
    > npm run dev











# Meu MANUAL GIT E GITHUB
by Fernando Tunouti

---

RESUMO DOS CÓDIGOS
---

* inicia o versionamento de uma pasta específica
    >git init
* adiciona um arquivo em 'Stage'
    >git add
* Salva o arquivo ficando pronto para envio para o GITHUB
	> git commit -m "---algum comentário"
* faz a conexação do repositório local para o repositório do GITHUB
	>git remote add origin git@github.com:seuusuario/seurepositorio
* envia arquivos commitados para o gitHUB no branch main
	>git push -u origin main 
* verifica o status dos arquivos git
	>git status           
* nomeia como main o branch principal
	>git branch -M main

---

### Para iniciar o versionamento de um projeto com o GIT siga a os passoas a seguir:

1. inciar criando a pasta local do projeto 
	> EX: /HOME/FTUNOUTI/CODIGOS/NOVO_PROJETO/
			
1. Dentro da pasta criada digitar o comando: 
	> git init
			
	* após o comando o git deverá gerar uma pasta .git para controle do versionamento
1. APÓS A CRIAÇÃO DE DIVERSOS ARQUIVOS DO PROJETO NESTA PASTA DIGITE : 
	> git add .
			
	* Este comando irá colocar todos os arquivos adicionados no 'STAGE', aguardando serem comitados.
---

## Após todos os arquivos serem colocados em 'STAGE' estes já podem ser salvos com versionados com commit:
1. PARA ISTO DIGITE O COMANDO:
    >git commit -m " ....algum comentario"
---

### Após os arquivos serem salvos (COMMIT), podemos então enviar para o repositório no GITHUB


1. PARA ENVIAR ARQUIVO GITHUB:
	1. FACA LOGIN NO SITE GITHUB 
	1. CRIE O REPOSITÓRIO ONDE SERÃO ARMAZENADOS OS ARQUIVOS
	1. APÓS CRIADO O REPOSITÓRIO LOCALIZE O COMANDO CORRESPONDENTE SSH, (ex. git remote ass origin git@github.com:seuusuario/seurepositorio)
			
	1. RETORNE À PASTA LOCAL DO SEU PROJETO /HOME/CODIGOS/NOVO_PROJETO/
	1. UTILIZE O COMANDO COPIADO ANTERIORMENTE : 
			git remote add origin git@github.com:seuusuario/seurepositorio
			
	1. UTILIZE O COMANDO : 
			push -u origin main
----

### Para gerar chave SSH:

1. DIGITE O COMANDO:
 $ ssh-keygen -t ed25519 -C "seu_email@host.com"
 
1. copie a chave gerada
NA SUA PÁGINA DO GITHUB, VÁ EM SETTINGS E em SSH and GPG keys
clique em New SSH key
cole o código o código gerado e nomeie-o com o nome de sua preferência



	
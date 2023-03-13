MANUAL GIT E GITHUB

by Fernando Tunouti
-

Para iniciar o versionamento de um projeto com o GIT siga a os passoas a seguir:
-

1. CRIAR A PASTA DO PROJETO 
			EX: /HOME/FTUNOUTI/CODIGOS/NOVO_PROJETO/
			
1. DENTRO DA PASTA CRIADA DIGITAR O COMANDO : 
			git init
			
1. ESTE COMANDO IRÁ GERAR OS ARQUIVOS INCIAIS DO GIT PARA O VERSIONAMENTO DO PROJETO
1. APÓS A CRIAÇÃO DE DIVERSOS ARQUIVOS DO PROJETO NESTA PASTA DIGITE : 
			git add .
			
1. ESTE COMANDO IRÁ COLOCAR TODOS OS ARQUIVOS NO 'STAGE', AGUARDANDO O COMMIT.
1. APÓS TODOS OS ARQUIVOS FOREM COLOCADOS EM 'STAGE' ESTES ARQUIVOS JÁ PODEM SER SALVOS E VERSIONADOS
1. PARA ISTO DIGITE O COMANDO:
		 	 git commit -m " ....algum comentario"
		 	 
1. APÓS OS ARQUIVOS SEREM SALVO (COMMIT), PODEMOS ENVIAR PARA O REPOSITÓRIO GITHUB


PARA ENVIAR ARQUIVO GITHUB:
1. FACA LOGIN NO SITE GITHUB 
1. CRIE O REPOSITÓRIO ONDE SERÃO ARMAZENADOS OS ARQUIVOS
1. APÓS CRIADO O REPOSITÓRIO LOCALIZE O COMANDO CORRESPONDENTE SSH, (ex. git remote ass origin git@github.com:seuusuario/seurepositorio)
			
1. RETORNE À PASTA LOCAL DO SEU PROJETO /HOME/FTUNOUTI/CODIGOS/NOVO_PROJETO/
1. UTILIZE O COMANDO COPIADO ANTERIORMENTE : 
			git remote add origin git@github.com:seuusuario/seurepositorio
			
1. UTILIZE O COMANDO : 
			push -u origin main


PARA GERAR CÓDIGO SSH:


1. DIGITE O COMANDO:
 $ ssh-keygen -t ed25519 -C "ftunouti@edu.unifil.br"
 
 
1. copie a chave gerada
NA SUA PÁGINA DO GITHUB, VÁ EM SETTINGS E em SSH and GPG keys
clique em New SSH key
cole o código o código gerado e nomeie-o com o nome de sua preferência


#RESUMO DOS CÓDIGOS

	*git init
	*git add
	*git commit -m "---algum comentário"
	*git remote add origin git@github.com:seuusuario/seurepositorio)
	*git push -u origin main
	
	
	
	*git status            ///verifica o status dos arquivos git
	*git branch -M main    ///nomeia como main o branch principal
	
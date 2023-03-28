# Como Trabalhar em Equipe ou Colaborar para um projeto no GitHub
1. Habilitando os colaboradores
    > No GitHub , o dono do repositório deverá inicialmente incluir os colaboradores, no menu _settings/collaborators_ do repositório a ser compartilhado.
    > Os convidados receberão mensagem para aceitar o convite.
  
1. Clonar o Repositório
    > No gitHub Desktop, inicie clonando a partir de uma url, informando o endereço do repositório _usuario/nome-repositório_

    ou..
    
    > Acessar o diretório local de trabalho pelo gitBash ou cmd do windows
    > dar o comando "git clone _https://github.com/projetoXXXX.git"_
    

1. Abrir o projeto na sua máquina na IDE:
    > Acessar o diretorio clonado na sua máquina
    > dar o comando "code .", para abrir o projeto no VsCode


1. Criar uma branch local:
    > abra um terminal do VScode , de preferencia o bash
    > digite o comando "git branch nomeXXX_da_branch"
    > após criada a branch, dar o comando "git checkout nomeXXX_da_branch" , para mudar a branch de trabalho
    > a pasta no bash passará de (main), para (nomeXXX_da_branch)

1. Fazer as modificaçoes e empurrar para branch local:
    > após realizar as modificações nesta branch
    > digite o comando "git add ."
    > digite o commando "git commit-m " XXXX comentários"

1. Empurrar para a branch remota:
    > No GitHub Desktop verificar na aba----->  se o Git está apontando para o repositório remoto correto 
    > no bash utilizar o comando: _git remote -v_
    > Se retornar com o endereço correto ir para o próximo passo
    > Senão utilizar o comando _git remote set-url origin <https-url>_
    > Verificar novamente com o comando:  _git remote -v_
    > Para empurrar para o GitHub: digite o comando "git push origin nomeXXX_da_branch"

1. Fazer o pull request para o dono do repositório
    > Acessar o repositório GitHub 
    > Verifique se há uma mensagem de Pull Request
    > Clicar no botão "Compare pull request" 
    > Opcional: Digite uma mensagem para o dono do repositório explicando sobre as modificações no projeto
    > Clique em "Create pull request" , para requisitar as mudanças
    > O dono do repositório, irá fazer as análises necessárias e se tiver tudo aprovado deverá fazer o "merge" no projeto.

Obrigado








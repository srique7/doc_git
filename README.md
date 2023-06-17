# Documentação Git
Documentação do git: Ajuda nos comandos iniciais.

Inicia o arquivo ".git/" para controlar a pasta.
````
git init 
````

Adiciona os arquivos modificado em uma área segura.
````
git add
````
Faz a validação dos arquivos dentro do projeto.
````
git status
````
Ele é responsável por criar uma nova versão do projeto com as referências do criador.(usado apenas quando o arquivo está verde)
````
git commit -m "<texto_da_modificação>" 
````
Apresenta dados que estão no commit.
````
git Log
````
limpa a tela do GIT
````
CTRL + L
````
Cria a branchs 
````
git checkout -b "<nome da branch>"
````
Muda a branch atual para outra branch que for escolhida.
````
git checkout "<nome da branch>" 
````
Carrega informações de uma branch para a branch que está ativa no momento.
````
git merge "<nome da branch>"
````
Exibe todos os detalhes da branch
````
gitk
````
baixa as informações do repositório remoto para o repositório local.
````
git clone "<https://github.com/srique7/doc_git.git>" 
````
Faz o upload das informações do repositório local para o repositório remoto. 
````
git push
````
Atualiza informações modificadas que estão no repositório remoto para o repositório local.
````
git pull 
````




ERROS : 
--
Caso o sistema solicite identificação no momento do commit
````
git config --global use.name "<seu_nome>"
````
````
git config --global use.email "<seu_email>"
````
ERRO: 403 : Resolve apagando as credenciais do sistema no gerenciamento de credenciais.

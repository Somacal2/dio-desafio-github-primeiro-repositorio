# Resumo **GIT** e **GITHUB**
###*Aulas DIO*###

**Comandos Básicos Via Terminal**

* *dir*: mostra uma lista de diretórios contidos naquela pasta específica (Windows);
* *ls*: mostra uma lista de diretórios contidos naquela pasta específica (MacOS e Linux);
* *cd*: possibilia a navegação entre pastas (Windows, MacOS e Linux);
* *cd/*: leva para a base da pasta (Windows, MacOS e Linux);
* *cd "nome da pasta"*: lpara entrar na página (Windows, MacOS e Linux);
* *cd ..*: para retroceder um nível de pasta (Windows, MacOS e Linux);
* *cls*: para limpar a tela (Windows);
* *clear*: para limpar a tela (MacOS e Linux);
* *usar a telha TAB*: autocompletar (Windows, MacOS e Linux);
* *mkdir "nome arquivo"*: criar uma pasta (Windows, MacOS e Linux);
* *echo "frase"*: printa a frase no terminal (Windows, MacOS e Linux);
* *echo "palavra" > "nome.extensão, exemplo: .txt"*: cria arquivo com o nome e extensão selecionada (Windows, MacOS e Linux);
* *del "nome arquivo"*: para deletar arquivo de uma pasta (Windows, MacOS e Linux);
* *rmdir /S /Q*: deleta uma parta ou diretório inteiro (Windows);
* *rm -rf "nome diretório*: deleta uma parta ou diretório inteiro (MacOS e Linux);

**Comandos Básicos Git Via Git Bash**
###*Para todos os tipos de OS's*###

* *ls -a*: mostrar arquivos ocultos;
* *git config -- global user.email "exemplo@exemplo.com"*: configuração de e-mail para realizar os commits;
* *git config -- global user.name "Exemplo"*: configuração de usuário para realizar os commits;
* *git add**: adicionar arquivo tosos os arquivos;
* *git commit -m**: commit inicial;

####Trocar e-mail e usuário####

* *git config -- list*: mostrar todas as informações, inclusive de e-mail e usuário cadastrado;
* *q*: para sair da função;

Caso seja necessário alterár o usuário e a senha, seguir os passos abaixo:
1. *git config --global -- unset user.email*: para limpar o e-mail;
2. *git config --global -- unset user.name*: para limpar o nome de usuário;
3. *git config --global -- user.email*: adicional e-mail de usuário;
3. *git config --global -- user.name*: adicional nome de usuário;

####Empurrar um repositório para o GitHub####
1. *git remote add origin "link gerado no GitHub"*
2. *git remote -v*: para ver se deu tudo certo
3. *git push origin master*

* *git status*: para ver o status do que está acontecendo ou precisa ser efetuado ou pendências;
* *git commit -m "adicionar descrição do commit"*:
* *git push origin master*: empurrar de fato para o GitHub;
* *git pull origin master*: empurrar de fato para o GitHub (caso seja necessário ou solicitado pelo terminal);
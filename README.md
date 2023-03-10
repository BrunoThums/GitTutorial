# GitTutorial
Dicas básicas para o git:
* Baixe e instale o git
* Use o clique com o direito do mouse dentro de alguma pasta e clique em “git bash here” para abrir o terminal do git
* `git init` Cria o repositório do git na pasta atual (para listar pasta ocultas, use `ls -a`)
* `git config --global user.email “seuEmailComAspas”` Configura o email do usuário para o git
* `git config --global user.name “SeuNomeComAspas”` Configura o email do usuário para o git
* `git remote add origin “linkSemAspas”` Associa o repositório online a sua pasta local, estabelecendo uma conexão
* `git remote -v` Lista as listas de repositórios remotos cadastrados
* `git add *` Adiciona todos conteúdos da pasta para o commit
* `git add “nomeDoArquivo”` Adiciona um arquivo específico para o git
* `git commit -m "tituloDoCommit"` Prepara o commit com um título (`-m`: mensagem)
* `git status` Verifica o status do git (commitado, falta commitar, etc)
* `git push origin main` Faz o upload do repositório para o git
* `git pull origin main` Faz o download do repositório para o seu dispositivo
* `git clone “urlSemAspas”` Faz o clone de um repositório na pasta atual
* Caso der erro em seu push, utilize o `-f` ao lado de push, ficando assim: `-- git push -f origin main` 

## Dica de Ouro:
* Para simplesmente usar `git push` ou `git pull`, sem a parte do `origin main`, basta executar este código:
* `git config --global --add --bool push.autoSetupRemote true`
* Assim facilita os commits! Em caso de dúvidas, consulte o manual usando `git --help` e procurando por `push.autoRemoteSetup`.

<p> Gostou do tutorial? Marque como favorito :star: <p> 
<p> Quer colocar mais detalhes ou sugerir uma correção? Abra uma issue :warning: <p> 

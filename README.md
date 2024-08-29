<h>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Versionamento de Código com Git e GitHub</span>
</h>


## Objetivo
Introduzir ao versionamento de código com Git e GitHub.

## Ferramentas
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
<br>

<h1>
O Git é um sistema de controle de versão distribuído que permite aos desenvolvedores gerenciar e acompanhar mudanças no código-fonte de um projeto
</h1>
<table>
Configurando o Git <br>
git config: Configura as opções de configuração para o Git.<br>
git config --global user.name "Seu Nome": Define o nome do usuário para todos os repositórios.<br>
git config --global user.email "seuemail@exemplo.com": Define o email do usuário para todos os repositórios.<br>
git config --list: Lista todas as configurações.<br>
Configurando o Repositório<br>
git init: Inicializa um novo repositório Git.<br>
git clone: Clona um repositório existente.<br>
git clone <url>: Clona o repositório da URL especificada.<br>

Verificando o Status<br>
git status: Mostra o status do repositório, incluindo quais arquivos foram modificados.<br>
Adicionando Arquivos<br>
git add: Adiciona arquivos ao índice.<br>
git add .: Adiciona todos os arquivos modificados.<br>
git add <arquivo>: Adiciona um arquivo específico.<br>
Removendo Arquivos<br>
git rm: Remove arquivos do índice e do diretório de trabalho.<br>
git rm --cached <arquivo>: Remove o arquivo do índice, mas mantém o arquivo no diretório de trabalho.
Commitando Mudanças<br>
git commit: Grava as mudanças no repositório.<br>
git commit -m "Mensagem do commit": Commita as mudanças com uma mensagem.<br>
Visualizando o Histórico<br>
git log: Mostra o histórico de commits.<br>
git log --oneline: Mostra o histórico de commits em uma linha.<br>
Desfazendo Mudanças<br>
git reset: Redefine o índice e o diretório de trabalho para o estado de um commit específico.<br>
git reset --hard <commit>: Redefine o índice e o diretório de trabalho para o estado do commit especificado.<br>
Branches e Tags<br>
git branch: Lista, cria ou exclui branches.<br>
git branch <nome>: Cria uma nova branch.<br>
git branch -d <nome>: Exclui a branch especificada.<br>
git checkout: Muda para a branch especificada.<br>
git checkout -b <nome>: Cria uma nova branch e muda para ela.<br>
git tag: Cria, lista, exclui ou verifica tags.<br>
git tag <nome>: Cria uma tag para o commit atual.<br>


Adicionando Remotos<br>
git remote: Gerencia os remotos conectados ao repositório.<br>
git remote add <nome> <url>: Adiciona um novo remote.<br>
Fetching e Pulling<br>
git fetch: Busca as mudanças do remote, mas não as mescla.<br>
git pull: Busca as mudanças do remote e as mescla.<br>

Pushing<br>
git push: Envia as mudanças para o remote.<br>
git push <nome> <branch>: Envia as mudanças para o branch especificado no remote.<br>

Rebasing<br>
git rebase: Reaplica commits em cima de outro branch.<br>
git rebase <branch>: Reaplica os commits do branch atual em cima do branch especificado.

Merging<br>
git merge: Combina as mudanças de outro branch.<br>
git merge <branch>: Combina as mudanças do branch especificado.<br>

Stashing<br>
git stash: Salva temporariamente as mudanças não commitadas.<br>
git stash pop: Aplica as mudanças salvas e remove-as do stash.<br>

Submodules<br>
git submodule: Gerencia submódulos.<br>
git submodule add <url> <caminho>: Adiciona um submódulo.<br>
git submodule update: Atualiza os submódulos.<br>

Git Hooks<br>
git hooks: Scripts executados automaticamente antes ou depois de eventos específicos do Git.<br>
Git LFS<br>
git lfs: Gerencia arquivos grandes.<br>
git lfs install: Instala o Git LFS.<br>
git lfs track: Adiciona arquivos para serem rastreados pelo Git LFS.<br>

Git Bisect<br>
git bisect: Encontra o commit que introduziu um bug.<br>
git bisect start: Inicia a busca pelo commit problemático.<br>
git bisect bad: Marca o commit atual como ruim.<br>
git bisect good <commit>: Marca o commit especificado como bom.<br>

Git Subtree<br>
git subtree: Gerencia submódulos como submódulos de subárvore.<br>
Git Subrepo<br>
git subrepo: Gerencia submódulos como submódulos de subrepositório.<br>
</table>
## Referências
- [GIT. Documentation](https://git-scm.com/doc)
- [GITHUB. Documentation](https://docs.github.com/)
- [GITHUB BLOG. February 28th DDoS Incident Report](https://github.blog/2018-03-01-ddos-incident-report/)
- [GITHUB BLOG. February 28th DDoS Incident Report](https://github.blog/2018-03-01-ddos-incident-report/)
- [GITHUB BLOG. Raising the bar for software security: GitHub 2FA begins March 13](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/)
- [GITHUB BLOG. Token authentication requirements for Git operations](https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/)
- [MICROSOFT. Microsoft to acquire GitHub for $7.5 billion](https:/news.microsoft.com/2018/06/04/microsoft-to-acquire-github-for-7-5-billion/)

##
<div align="center"></div>

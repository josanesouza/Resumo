<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Versionamento de Código com Git e GitHub</span>
</h1>


## Objetivo
Introduzir ao versionamento de código com Git e GitHub.

## Ferramentas
[![Git](https://img.shields.io/badge/Git-000?style=for-the-badge&logo=git&logoColor=E94D5F)](https://git-scm.com/doc) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://docs.github.com/)
<br>

<h1>
O Git é um sistema de controle de versão distribuído que permite aos desenvolvedores gerenciar e acompanhar mudanças no código-fonte de um projeto
    
Configurando o Git
git config: Configura as opções de configuração para o Git.
git config --global user.name "Seu Nome": Define o nome do usuário para todos os repositórios.
git config --global user.email "seuemail@exemplo.com": Define o email do usuário para todos os repositórios.
git config --list: Lista todas as configurações.
Configurando o Repositório
git init: Inicializa um novo repositório Git.
git clone: Clona um repositório existente.
git clone <url>: Clona o repositório da URL especificada.

Verificando o Status
git status: Mostra o status do repositório, incluindo quais arquivos foram modificados.
Adicionando Arquivos
git add: Adiciona arquivos ao índice.
git add .: Adiciona todos os arquivos modificados.
git add <arquivo>: Adiciona um arquivo específico.
Removendo Arquivos
git rm: Remove arquivos do índice e do diretório de trabalho.
git rm --cached <arquivo>: Remove o arquivo do índice, mas mantém o arquivo no diretório de trabalho.
Commitando Mudanças
git commit: Grava as mudanças no repositório.
git commit -m "Mensagem do commit": Commita as mudanças com uma mensagem.
Visualizando o Histórico
git log: Mostra o histórico de commits.
git log --oneline: Mostra o histórico de commits em uma linha.
Desfazendo Mudanças
git reset: Redefine o índice e o diretório de trabalho para o estado de um commit específico.
git reset --hard <commit>: Redefine o índice e o diretório de trabalho para o estado do commit especificado.
Branches e Tags
git branch: Lista, cria ou exclui branches.
git branch <nome>: Cria uma nova branch.
git branch -d <nome>: Exclui a branch especificada.
git checkout: Muda para a branch especificada.
git checkout -b <nome>: Cria uma nova branch e muda para ela.
git tag: Cria, lista, exclui ou verifica tags.
git tag <nome>: Cria uma tag para o commit atual.


Adicionando Remotos
git remote: Gerencia os remotos conectados ao repositório.
git remote add <nome> <url>: Adiciona um novo remote.
Fetching e Pulling
git fetch: Busca as mudanças do remote, mas não as mescla.
git pull: Busca as mudanças do remote e as mescla.
Pushing
git push: Envia as mudanças para o remote.
git push <nome> <branch>: Envia as mudanças para o branch especificado no remote.
Rebasing
git rebase: Reaplica commits em cima de outro branch.
git rebase <branch>: Reaplica os commits do branch atual em cima do branch especificado.
Merging
git merge: Combina as mudanças de outro branch.
git merge <branch>: Combina as mudanças do branch especificado.
Stashing
git stash: Salva temporariamente as mudanças não commitadas.
git stash pop: Aplica as mudanças salvas e remove-as do stash.
Submodules
git submodule: Gerencia submódulos.
git submodule add <url> <caminho>: Adiciona um submódulo.
git submodule update: Atualiza os submódulos.

Git Hooks
git hooks: Scripts executados automaticamente antes ou depois de eventos específicos do Git.
Git LFS
git lfs: Gerencia arquivos grandes.
git lfs install: Instala o Git LFS.
git lfs track: Adiciona arquivos para serem rastreados pelo Git LFS.
Git Bisect
git bisect: Encontra o commit que introduziu um bug.
git bisect start: Inicia a busca pelo commit problemático.
git bisect bad: Marca o commit atual como ruim.
git bisect good <commit>: Marca o commit especificado como bom.
Git Subtree
git subtree: Gerencia submódulos como submódulos de subárvore.
Git Subrepo
git subrepo: Gerencia submódulos como submódulos de subrepositório.
</h1>


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

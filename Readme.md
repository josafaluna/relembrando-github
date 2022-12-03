# Github - Git Course

Arquivo da aula de Git e Github

Status dos arquivos

- untracked: Não marcado, arquivo que foi adiciondo mas git ainda não o reconheceu
- unmodified: quando o arquivo é adicionado no git e ainda não foi modificado
- modified: quando o arquivo é modificado
- staged: area aonde será criado a versão e pode ser criado o commit

Noções básicas de git

Iniciando um repositório
git init

# Git LOG

git log
git log --decorate
git log --author="Josa"
git shortlog
git shortlog -sn
git log --graph
git show hash

# Git Diff

gi diff
git diff --name-only

# Git Reset/Checkout

Tirando do Staged
git reset HEAD Readme.md

Removendo as últimas modificações
git checkout Readme.md

# Git reset

Obs: sempre escolher quando commit anterior ao que queremos remover
Três tipos de reset

Retira o último commit, o arquivo permabece em staged pronto para outro commit
git reset --soft hash

Retira o último commit, e volta os arquivos para modified
git reset --mixed hash

Retira tudo o que foi feito no commit
git reset --hard hash

# Git Remote

Ligando o seu repositório remoto com o local
git remote add origin caminho_do_repositorio_remoto

Caminho do repositório
git remote -v


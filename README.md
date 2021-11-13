Essa formatação é a chamada: Markdown

# Curso de Front-end
#### EBAC

# GIT
## Controle de Versionamento
- Histórico
- Controle de versão
- Quem alterou
- O que alterou
- Quando alterou
- Todos os arquivos
- Evolução continua


## Instalação do Git

Windows https://git-scm.com/download/win
Linux (apt-get): sudo apt-get install git
Mac (brew install git)

## Criar conta no Github

## Clonar o projeto
git clone https://github.com/higor-mobile/curso-frontend.git


## Commits
Informações de alterações
- Após testado tod seu código
- git add *
- git commit -m "Aqui vai a mensagem"
- git push (enviar alterações para o repositório)
- git pull (puxar / trazer alterações do Github para minha máquina)

## GitFlow
- Fluxo do Git

## Branchs
São ramificações  / versões paralelas

- main / master (vai para produção, quando o projeto é público)
- develop
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.0

Comandos
git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)
## Merge
Mescla de branchs


git merge

### Pull Requests
Mescla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente

### Configurando o GitFlow
git flow init
git flow feature start {nome-de-feature}


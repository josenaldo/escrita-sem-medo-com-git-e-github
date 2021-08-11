# Guia Rápido

Configurando o Git

git config --global user.name "João da Silva"
git config --global user.email joao.da.silva@example.com

Inicializando um repotisório Git

mkdir pasta_teste
cd pasta_teste
git init

Fluxo de trabalho do Git

Fluxo normal
    Criar repositório no github
    Clonar repositório
    Adicionar/editar conteúdo
    git add
    git commit
    git push
Trabalhando com ramos
    git checkout -b funcionalidade
    git checkout main
    git branch -d funcionalidade
    git push origin funcionalidade
Fazendo merge
    git checkout main
    git merge funcionalidade
Trabalhando com mais de uma pessoa
E quando ocorrer um problema?
# prova_a2

mayqueragg41@outlook.com

GabriellyMayquera31102024030780

passo a passo:
Criar o repositório no github(deixar publico, aicionar o README file, adicionar o .gitignore do VisualStudio).
Clonaro repositório na máquina, através do terminal aberto no folder da prova.

> git clone "link"

Adicionar o arquivo de teste para dentro do repositório

Criar a solução:
> dotnet new sln --output Rafael
> 
> cd Rafael
> 
> dotnet new web -n Rafael
> 
> dotnet sln add Rafael

Colocar o arquivo de teste dentro do projeto
Commit para testar:

> git status
> 
> git add .

> git commit -m "Mensagem commit"
>
> git push

Comandos para instalar bibliotecas:

> dotnet add package Microsoft.EntityFrameworkCore.Sqlite
> 
> dotnet add package Microsoft.EntityFrameworkCore.Design

Criar a pasta Models

Criar a primeira migração:

>dotnet ef migrations add InitialCreate
>
>dotnet ef database upddate

Links do notion importantes:
CRUD com Entity Framework

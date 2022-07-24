# Comandos iniciais:
``` bash
  mkdir api-desafio21dias-materiais
  cd api-desafio21dias-materiais
  dotnet new webapi
```

# Comandos git:
``` bash
  code .gitignore 
```
#### Gerei o conteúdo para ignorar como (Windows, Linux, Mac, DotnetCore, VisualStudioCore) no link: https://www.toptal.com/developers/gitignore
- Criei o repositório e rodei os comandos

``` bash
  git init
  git add .
  git commit -m "Iniciando projeto"
  git remote add origin git@github.com:torneseumprogramador/api-desafio21dias-materiais.git
  git branch -M main
  git push -u origin main
```

# Componentes instalados:
``` bash
  PackageReference Include="EntityFrameworkPaginateCore" Version="2.1.0" />
    <PackageReference Include="Swashbuckle.AspNetCore" Version="5.6.3" />
    <PackageReference Include="Microsoft.EntityFrameworkCore" Version="6.0.0" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="6.0.0" />
```

# Comandos para migração para criar:
``` bash
dotnet tool install --global dotnet-ef
dotnet ef migrations add MateriaisAdd
dotnet ef database update
```

# Comandos para atualizar database
#### Caso você esteja usando esta aplicação com o código clonado, rodar o comando abaixo
``` bash
dotnet ef database update
```
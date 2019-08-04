### Criar solution
 
```dotnet new sln  --name CursoUdemyApiDDD```
 
### Criar projeto console dentro de uma pasta
 
```dotnet new console -n ConsoleTeste -o ConsoleTeste```
 
### Lincar projeto na solução
 
```dotnet sln  add ConsoleTeste\```

### Listar projetos dentro da solução

```dotnet sln list```

### Executar console

```dotnet run```

### Remover projeto da solução

```dotnet sln remove ConsoleTeste\```

### Remover certificados de desenvolvimento

```dotnet dev-certs https --clean```

### Adicionar certificados de desenvolvimento

```dotnet dev-certs https --trust```

### Criar projeto WebAPI

```dotnet new webapi -n CursoUdemyApiDDD -o CursoUdemyApiDDD```

### Criar camada Application

```dotnet new classlib -n "CursoUdemyApiDDD.Application" -o CursoUdemyApiDDD.Application -f netcoreapp3.0```





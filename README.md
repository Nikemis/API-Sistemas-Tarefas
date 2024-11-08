
# Sistema gerenciador de tarefas
Este é um sistema gerenciador de tarefas desenvolvido em C# utilizando Entity Framework. A aplicação permite cadastrar, editar, excluir e visualizar tarefas, ajudando a organizar melhor a rotina diária.


## Funcionalidades

- Cadastro de tarefas: Permite criar novas tarefas e salvar no banco de dados.
- Leitura de tarefas: Você pode listar todas as tarefas cadastradas.
- Atualização de tarefas: Permite editar as tarefas existentes.
- Exclusão de tarefas: Você pode remover tarefas que não são mais necessárias.

Este sistema utiliza o padrão CRUD (Create, Read, Update, Delete) para gerenciar as tarefas.
## Tecnologias Utilizadas
- C#: Linguagem de programação principal.
- ASP.NET Core Web API: Framework utilizado para a criação da API
- Entity Framework Core: ORM utilizado para a comunicação com o banco de dados
- SQL Server

## Como Executar o Projeto

Requisitos
- .NET 6 ou superior 
- SQL Server 
- Visual Studio ou Visual Studio Code

 ## Passos para execução local:

1. Clonar o repositório:

```bash
  git clone https://github.com/Nikemis/API-Sistemas-Tarefas.git
```

2. Restaurar pacotes NuGet: Dentro da pasta do projeto, execute:
```bash
  dotnet restore
```

3. Configurar a string de conexão: No arquivo appsettings.json, configure a string de conexão com seu banco de dados. Exemplo:

```bash
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=TaskManagementDb;Trusted_Connection=True;"
}
```

4. Aplicar migrações e atualizar o banco de dados:

```bash
  dotnet-ef database update
```

5. Executar o projeto:
```bash
  dotnet run
```


## Contributing

Contribuições são bem-vindas! Se você deseja colaborar com o projeto, siga os seguintes passos:

1. Fork o repositório.
2. Crie uma branch com sua feature (git checkout -b feature-nome-da-feature).
3. Faça o commit das suas mudanças (git commit -m 'Adicionando nova funcionalidade').
4. Envie para o repositório remoto (git push origin feature-nome-da-feature).
5. Abra um pull request.

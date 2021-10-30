Sistema de Cadastro com ASP Web .NET Core
.NET Core Version: 3.1

Inicializando o projeto:

- Instalações de pacotes realizadas:
	Ent Framework utilizando o SQL Server
	Install-Package Microsoft.EntityFrameworkCore.SqlServer

	Ferramentas do Entity Framework para utilizar as Migrations
	Install-Package Microsoft.EntityFrameworkCore.Tools

- Adicionando Migration
	Add-Migration InitialCreate
	Update-Database
	Add-Migration TabelaProduto
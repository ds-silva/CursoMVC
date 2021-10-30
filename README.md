<h1>Sistema de Cadastro com ASP Web .NET Core</h1> <br/>
<h2>.NET Core Version: 3.1</h2> <br/>

<h3>Inicializando o projeto: </h3>

- <h3>Instalações de pacotes realizadas:</h3>
<ul>
	<li>Entity Framework utilizando o SQL Server</li>
		<ul>
			<li>Install-Package Microsoft.EntityFrameworkCore.SqlServer</li>
		</ul>
	<li>Ferramentas do Entity Framework para utilizar as Migrations</li>
	<ul>
		<li>Install-Package Microsoft.EntityFrameworkCore.Tools</li>
	</ul>
</ul>
- <h3> Adicionando Migration (Comandos abaixo):</h3>
<ul>
	<li>Add-Migration InitialCreate</li>
	<li>Update-Database</li>
	<li>Add-Migration TabelaProduto</li>
</ul>
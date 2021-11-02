<h1>Solução de cadastro com .NET Core</h1><br/>
<h4>A Solução contém um sistema em ASP.NET Core Web App com MVC, uma ASP.NET Core Web API, e um projeto de testes com xUnit.</h4><br/>

<h4>Informações do Projeto</h4>
<ul>
	<li>.NET Core Version: 3.1</li>
</ul>

<h4>Inicializando o projeto: </h4>
<h4>Instalações de pacotes realizadas:</h4>
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
<h4> Adicionando Migration (Comandos abaixo):</h4>
<ul>
	<li>Add-Migration InitialCreate</li>
	<li>Update-Database</li>
	<li>Add-Migration TabelaProduto</li>
</ul>

<h1>API em ASP .NET Core Web App</h1> <br/>
<h4>Informações do Projeto</h4>
	<ul>
		<li>.NET Core Version: 3.1</li>
		<li>Swagger Version: 5.0.0</li>
		<ul>
			<li>Build - XML Documentation: Enabled</li>
			<li>Debug - Lauch Browser: swagger</li>
		</ul>
	</ul>

<h1>Projeto de Testes com xUnit</h1> <br/>
<h4>Informações do Projeto</h4>
	<ul>
		<li>.NET Core Version: 3.1</li>
		<ul>
			<li>Moq Version: 4.16.1</li>
		</ul>
	</ul>

<h1>Publicando APP na Nuvem da Azure</h1> <br/>
<h4>Necessário para o funcionamento das Migrations</h4>
	<ul>
		<li>dotnet tool install --global --version 3.0.0 dotnet-ef</li>
	</ul>
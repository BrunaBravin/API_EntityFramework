# API Entity Framework

### Informações sobre o projeto

<p>A API foi criada utilizando SQL Server, um banco de dados da Microsoft. Para que o projeto funcione em sua máquina é necessário que o SQL Server esteja instalado nela, para instalar, visite o link: 
  <a href="https://www.microsoft.com/pt-br/sql-server/sql-server-downloads" target="_blank">Instalação SQL Server</a></p>

### Como rodar o projeto:

<ul>
<li>No arquivo "appsettings.Development" modifique a conexão padrão para o indicado.</li>
<li>Coloque o seguinte comando no terminal para que a tabela "Contatos" seja criada em seu banco de dados: <br><b>dotnet-ef migrations add CriacaoTabelaContato</b></li>
<li>Em seguida coloque o seguinte comando no terminal para aplicar as alterações no seu banco de dados: <br><b>dotnet ef database update</b> </li>
<li>:sparkles: prontinho! a aplicação está funcionando! :sparkles:, para executá-la coloque o comando no terminal: <br><b>dotnet watch run</b> </li>
</ul>

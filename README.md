# Projeto Fictius Clean

<h2><i> api rest e web api </i></h2>

Ferramenta produzida com Entity Framework + SQL Server, usei um banco de dados LocalDB para fazer os testes;

no arquivo appsettings.json esta a conexao com o localdb;
![image](https://user-images.githubusercontent.com/28540187/160851056-fb2fe4cd-7130-415c-bc9a-f91a3575b43a.png)


Após abrir a aplicação no VisualStudio abrir o Console PowerShell e executar os comandos

add-migrations
update-database<br>

![image](https://user-images.githubusercontent.com/28540187/160844513-afee2859-65e0-42ca-b6c6-10a4526b2163.png)

*Para o entity framework criar o banco de dados e aplicar as alteracoes;* <br>

Após feito isso, dentro das propriedades da Aplicacao, você pode selecionar qual projeto irá inicializar.

![image](https://user-images.githubusercontent.com/28540187/160850720-ca1151a7-389b-4331-8659-431eb955a763.png)

![image](https://user-images.githubusercontent.com/28540187/160844437-588ae821-4414-44d4-b301-81b3acd00dda.png)

<i>Ja esta tudo configurado para a porta 5001, porem caso necessário rodar apenas a Api FicticiusClean para verificar a porta que esta sendo utilizzado, caso o VisualStudio jogue a API para outra porta, senao deixar as duas apliações para iniciar e usar a WebAPi de Consumo</i>

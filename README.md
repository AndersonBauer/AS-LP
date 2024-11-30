Nesse projeto, criamos uma API de para Fornecedores e Pedidos sem relacionamento.

Para poder testar esse projeto você vai precisar do Postman instalado ou o swagger, no meu caso eu usei o Postman para realizar os testes e consultas.
Ao dar o comando dotnet run no terminal powershell você poderá verificar qual o endereço HTTP em que ele está sendo usado.
No meu caso, está na porta http://localhost:5042(pedidos ou fornecedores) dependendo de qual deles você quer usar.
As requisições HTTP que eu usei são a GET, em que temos dois tipos, tanto a GETALL que pega todos as entidades, quanto a GETID que pega apenas um ID especifico, também temos a POST que criamos uma nova entidade passando pelo body da requisição definimos quais serão as informações que ela possuirá, temos o PUT também que será onde editaremos as informações da entidade, e por fim o DELETE que faz a excluisão de entidades do banco de dados.
Falando em banco de dados o arquivo banco.db é onde as informações são guardadas no banco, como tabelas.

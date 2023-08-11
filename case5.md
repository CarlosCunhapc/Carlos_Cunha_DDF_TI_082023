# Case 5:

### SELECT * 
### FROM users_emails 
### WHERE registration_date >= DATE_SUB(CURRENT_DATE, INTERVAL 30 DAY);

1. SELECT *: Especifica as colunas que você deseja buscar da tabela.* é um caracter que seleciona todas as colunas; 
2. FROM users_emails: Especifica a tabela que buscará os dados; 
3. WHERE registration_date >= DATE_SUB(CURRENT_DATE, INTERVAL 30 DIAS); Esta é a condição de filtragem que busca os usuários que se cadastraram nos últimos 30 dias. 
4. registration_date: Refere-se à coluna da tabela "users_emails" que armazena a data de registro dos usuários;
5. CURRENT_DATE: Função que retorna a data atual; 6. DATE_SUB(CURRENT_DATE, INTERVAL 30 DAY): Função que calcula uma data que subtrai um intervalo de 30 dias da data atual;
7. '>=' : Comparação que verifica se a data de registro de um usuário é maior ou igual à data calculada há 30 dias atrás;
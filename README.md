# PROJETO ALL FOR ONE

Projeto desenvolvido no módulo de Back-End do curso de desenvolvimento web da  Trybe

## 🎯 Objetivo

Projeto com o codinome All For One em que praticará todos os conceitos de SQL já ensinados na plataforma de aprendizagem do curso de desenvolvimento web da Trybe.

## 📝 Habilidades adquiridas

 1. Compreender o que é uma query SQL e quais são seus tipos de comando;
 2. Gerar valores com SELECT;
 3. Selecionar colunas individualmente com SELECT;
 4. Renomear e gerar colunas em uma consulta com AS;
 5. Concatenar colunas e valores com CONCAT;
 6. Remover dados duplicados em uma consulta com DISTINCT;
 7. Contar a quantidade de resultados em uma consulta com COUNT;
 8. Limitar a quantidade de resultados em uma consulta com LIMIT;
 9. Pular resultados em uma consulta com OFFSET;
10. Ordenar os resultados de uma consulta com ORDER BY.
11. Filtrar resultados de consultas com o WHERE.
12. Utilizar operadores booleanos e relacionais em consultas.
13. Criar consultas mais dinâmicas e maleáveis com LIKE.
14. Fazer consultas que englobam uma faixa de resultados com IN e BETWEEN.
25. Encontrar e separar resultados que incluem datas.


  ## :pushpin: Tecnologias e linguagens utilizadas no desenvolvimento
  ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
  ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)


<details>
  <summary><strong>:heavy_check_mark: Requisitos do projeto  </strong></summary><br />

 - [x] Exiba apenas os nomes dos produtos na tabela products.
 - [x] Crie um filtro de texto para a tabela.
 - [x] Escreva uma query que exiba os valores da coluna que representa a primary key da tabela products.
 - [x] Conte quantos registros existem na coluna product_name da tabela products.
 - [x] Monte uma query que exiba os dados da tabela products a partir do quarto registro até o décimo terceiro.
 - [x] Exiba os dados das colunas product_name e id da tabela products de maneira que os resultados estejam em 
       ordem alfabética dos nomes.
 - [x] Mostre apenas os ids dos 5 últimos registros da tabela products (a ordenação deve ser baseada na coluna id).
 - [x] Faça uma consulta na tabela employees que retorne o nome completo da pessoa colaboradora (colunas 
       first_name e last_name) com o nome full_name e também a localização completa (colunas city, state_province 
       e address) com o nome location.
 - [x] Mostre todos os dados da tabela purchase_orders em ordem decrescente, ordenados por created_by em que o 
       created_by é maior ou igual a 3.
 - [x] Exiba os dados da coluna notes da tabela purchase_orders em que seu valor de Purchase generated based on 
       Order é maior ou igual a 30 e menor ou igual a 39.
 - [x] Mostre as submitted_date de purchase_orders em que a submitted_date é do dia 26 de abril de 2006.
 - [x] Mostre os resultados da coluna supplier_id da tabela purchase_orders em que o supplier_id seja maior ou 
       igual a 1 e menor ou igual 3.
 - [x] Mostre o supplier_id das purchase_orders em que o supplier_id seja 1 ou 3.
 - [x] Mostre somente as horas (sem os minutos e os segundos) da coluna submitted_date de todos registros da 
       tabela purchase_orders.(No resultado, a hora extraída da coluna submitted_date deve ser chamada de 
       submitted_hour)
 - [x] Exiba a submitted_date das purchase_orders que estão entre 2006-01-26 00:00:00 e 2006-03-31 23:59:59.
 - [x] Mostre os registros das colunas id e supplier_id das purchase_orders em que os supplier_id sejam tanto 1, 
       ou 3, ou 5, ou 7.
 - [x] Mostre todos os registros de purchase_orders que tem o supplier_id igual a 3 e status_id igual a 2.
 - [x] Mostre a quantidade de pedidos que foram feitos na tabela orders pelo employee_id igual a 5 ou 6, e que 
       foram enviados através do método(coluna) shipper_id igual a 2.
 - [x] Adicione à tabela order_details um registro com order_id: 69, product_id: 80, quantity: 15.0000, 
       unit_price: 15.0000, discount: 0, status_id: 2, date_allocated: NULL, purchase_order_id: NULL e 
       inventory_id: 129.
 - [x] Adicione com um único INSERT, duas linhas à tabela order_details com os mesmos dados do requisito 20.
 - [x] Atualize todos os dados da coluna discount, na tabela order_details, para 15.
 - [x] Atualize os dados da coluna discount da tabela order_details para 30, onde o valor na coluna unit_price 
       seja menor que 10.0000.
 - [x] Atualize os dados da coluna discount da tabela order_details para 45, onde o valor na coluna unit_price 
       seja maior que 10.0000 e o id seja um número entre 30 e 40.
 - [x] Delete todos os dados em que a unit_price da tabela order_details seja menor que 10.0000.
 - [x] Delete todos os dados em que a unit_price da tabela order_details seja maior que 10.0000.
 - [x] Delete todos os dados da tabela order_details.


      
</details>

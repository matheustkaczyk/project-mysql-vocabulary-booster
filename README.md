Projeto desenvolvido durante o curso de desenvolvimento de software na Trybe. O objetivo foi desenvolver queries SQL mais complexas, fazendo relacionamentos, criando views, stored procedures e functions.

Data de entrega: 28/09/2021

# Habilidades
  * Criar condicionais no **SQL** usando **IF** e **CASE**

  * Manipular _strings_ no **SQL**

  * Usar as diversas funções matemáticas do **MySQL**

  * Extrair informações específicas sobre datas de uma tabela

  * Utilizar as funções de agregação **AVG**, **MIN**, **MAX**, **SUM** e **COUNT**

  * Exibir e filtrar dados de forma agrupada com **GROUP BY** e **HAVING**

  * Utilizar **INNER JOIN**, **LEFT JOIN**, **RIGHT JOIN** para combinar dados de duas ou mais tabelas

  * Utilizar **SELF JOIN** para fazer join de uma tabela com ela própria

  * Utilizar SUBQUERIES

  * Criar queries mais eficientes através do EXISTS

  * Montar blocos de código **SQL** reutilizáveis com **STORED PROCEDURES** e **STORED FUNCTIONS**

---

# Lista de requisitos

## 1 - Exiba os países e indicando se cada um deles se encontra ou não na região formada pela Europa

## 2 - Exiba os cargos com seu nível de renumeração associado, com base no salário máximo do cargo

## 3 - Exiba os cargos com a diferença entre seus salários máximo e mínimo

## 4 - Exiba a média salarial e o nível de senioridade de todas as pessoas empregadas, agrupadas pelo cargo

## 5 - Exiba os cargos com sua variação salarial e suas médias máxima e mínima mensal, considerando salários máximo e minímo como anuais

## 6 - Faça um relatório que mostra o histórico de cargos das pessoas empregadas

## 7 - Faça um relatório que mostra o histórico de cargos das pessoas empregadas que iniciaram seus cargos nos meses de janeiro, fevereiro ou março

## 8 - Exibe todas as **pessoas consumidoras** cujos pedidos já foram enviados pelas empresas `"Speedy Express"` ou `"United Package"`

## 9 - Exibe todos as pessoas funcionárias que já realizaram algum pedido, mostrando também seu total de pedidos feitos

## 10 - Exibe todos os produtos que já foram pedidos, que possuem uma média de quantidade nos pedidos registrados acima de `20.00`

## 11 - Exibe todas as pessoas clientes **que possuem compatriotas**, mostrando a quantidade de compatriotas para cada pessoa cliente

## 12 - Faça um relatório que lista todas as pessoas funcionárias **que possuem o mesmo cargo**

## 13 - Exibe todos produtos **que já tiveram um pedido associado requerindo uma quantidade desse produto maior que 80**

## 14 - Considerando o conjunto formado pelas pessoas consumidoras e empresas fornecedoras de produtos, queremos saber quais são os cinco primeiros países distintos, em ordem alfabética, presentes nesse conjunto

## 15 - Crie uma procedure chamada `buscar_media_por_cargo` que recebe como parâmetro o nome de um cargo e em retorno deve mostrar a média salarial de todas as pessoas que possuem esse cargo

## 16 - Crie uma função chamada `buscar_quantidade_de_empregos_por_funcionario` no banco de dados `hr` que, ao receber o **email de uma pessoa funcionária**, retorne a quantidade de empregos **presentes em seu histórico**

## 17 - Crie uma TRIGGER que, a cada nova inserção realizada na tabela `orders`, insira automaticamente a data atual na coluna `OrderDate`

## BÔNUS:

### 18 - Faça um relatório que mostra o **histórico de cargos das pessoas empregadas**, mostrando as datas de início e de saída, assim como os anos que ela ficou nesse cargo

### 19 - Crie uma função chamada `exibir_quantidade_pessoas_contratadas_por_mes_e_ano` no banco de dados `hr` que, dados o mês e ano como parâmetros nessa ordem, retorna a quantidade de pessoas funcionárias **que foram contratadas** nesse mês e ano

### 20 - Toda pessoa funcionária no banco `hr` possui um histórico completo de cargos. Logo, crie uma procedure chamada `exibir_historico_completo_por_funcionario` que, dado o e-mail de uma pessoa funcionária, retorna todos os cargos em seu histórico

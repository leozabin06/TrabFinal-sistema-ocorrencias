# TrabFinal-sistema-ocorrencias

"Registro de Ocorrências"

DOCUMENTO DE REQUISITOS:
Visão Geral do Sistema: O sistema deve registrar as chamadas (ocorrências) feitas ao departamento de informática da empresa. Às ocorrências são atribuídas informações relacionadas ao departamento que reportou a ocorrência e, 
também, ao funcionário alocado para resolver a ocorrência registrada. 

Requisitos Funcionais
R1 - O sistema deve manter o cadastro de departamentos, assim como sua alteração, ambos realizados pelo diretor; e as informações a serem guardadas são: código, nome, descrição, status (campo texto informando se o departamento está ativo ou inativo.

R2 - O sistema deve manter o cadastro de diretor; e as informações a serem guardadas são: matrícula, nome, status (campo texto informando se o diretor está ou não em exercício.

R3 - O sistema deve manter o cadastro de gerente de departamento; e as informações a serem guardadas são: matrícula, nome, departamento o qual gere, status (campo texto informando se o gerente está ativo ou inativo.

R4 - O sistema deve manter o cadastro de funcionários, assim como sua alteração, ambos realizados pelo gerente; e as informações a serem guardadas são: matrícula, nome, departamento ao qual pertence, status (campo texto 
informando se o funcionário está ativo ou inativo.

R5 - O sistema deve manter o registro de ocorrências, realizado pelo gerente do departamento reportante, assim como sua alteração e visualização, ambos realizados pelo gerente e pelo funcionário alocado, cada um com suas limitações; e cada ocorrência deve conter: número, descrição, data da ocorrência, departamento reportante (código), funcionário alocado matrícula), data limite para solução, status temporário (campo texto, alterável pelo funcionário alocado, informando se a ocorrência está aberta ou encerrada), status definitivo (campo texto, alterável pelo gerente do departamento reportante, informando se a ocorrência está aberta ou encerrada.

R6 - Validação: Ao registrar uma ocorrência, é necessário validar a data da ocorrência para que não seja possível informar uma data futura; já com relação a data limite para solução da ocorrência, deve ser obrigatoriamente uma data 
futura; além disso, o funcionário alocado deve necessariamente ser do departamento de informática.

Banco de dados em MYSQL


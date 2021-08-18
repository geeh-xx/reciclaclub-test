

# Desafio Tecnico

Desafio criado para o processo seletivo do recicla-club, leia bem este readme e caso tenha alguma duvida não existe em perguntar

## Problema a ser resolvido

Temos um restaurante Banana Grill onde recentemente tivemos um aumento consideravel no numero de clientes, devido a isso a quantidade de pedidos cresceu muito
oque acabou gerando uma  confusão tanto na hora dos garçons anotarem os pedidos, no chefe para receber os pedido, no caixa para fazer controle das mesas e do gerente para ter o controle da casa. 
Devido a esse problemas resolvemos encomendar um sistema onde podemos ter a possibilidade de esse controle.

### Requisitos de negocios/ Oque deve ser implementado

Precisamos que voce desenvolva um sisema para nos ajudar a gerir o Banana Grill, e esse sistema precisa ter as seguintes funcionalidades:

1 - Abrir  Mesa - Sistema deve ter a possibilidade de cadastrar uma mesa
    -> 1.1 - Toda mesa deve ter um numero associada a ela, esse numero e fornecido pelo garçom na hora de fazer a abertura da mesa. 
    -> 1.2 - Toda abertura de mesa deve ter uma data de abertura e fechamento vinculada a ela, para se saber quando foi feita sua abertura e fechamento

2 - Pedidos - Sistema deve ter a funcionalidade o cliente realizar pedidos e o garcom registrar
    -> 2.1 - Pedidos devem conter o nome do prato e o valor e  devem estar vinculados obrigatoriamente a uma mesa
    -> 2.2 - Uma mesa não ter mais de dois pedidos em aberto( não entregue para uma mesa ) ao mesmo tempo, isso devido ao nosso numero limitado de funcionarios.
    -> 2.3 - Somente uma mesa aberta pode realizar pedidos
    
3 - Fluxo de Caixa - O sistema deve ter a funcionalidade do gerente pode controlar o fluxo de caixa
    3-> 3.1 - Sistema deve ser capaz de gerar o faturamento total de uma determinada data 
    3-> 3.2 - Sistema deve ser capaz de saber qual foi a mesa que mais consumiu em uma determinada data
    3-> 3.3 - Sistema deve ser capaz de saber qual foi o prato que mais demorou a ser feito em uma determinada data
    
4 - Conta - Fechamento da Mesa
     4-> 4.1 - Sistema deve ser capaz gerar um total de gasto de de uma mesa a partir de seu numero (Obs: numero da mesa e diferente do id do banco)
     4-> 4.2 - Sistema deve ser capaz de detalhar os gastos detalhados ou seja de cada prato de uma mesa a partir de seu numero (Obs: numero da mesa e diferente do id do banco)
     4-> 4.3 - Sistema deve ser capaz de fechar a mesa e permitir uma nova abertura com clientes diferentes e a conta zerada, mas com o mesmo numero de mesa.
     4-> 4.4 - Sistema deve permitir o cliente pedir uma conta parcial ou seja solicitar uma conta detalhando o total dos seus gastos, mas sem fechar a mesa

### Requisitos tecnicos
 
```
- back end do projeto deve ser desenvolvido usando como base o framework SpringBoot.

- Deve ser usado React para o desenvolvimento Front-End.

- Projeto deve ser testavel e funcionar no computador de quem ira fazer a avaliação

- Alem dos frameworks obrigatorios citados a cima, pode ser usado qualquer outra a sua vontade

```

### Bonus

Caso sobre tempo tente implementar as seguintes funcionalidade



3 - Fluxo de Caixa - O sistema deve ter a funcionalidade do gerente pode controlar o fluxo de caixa
    3-> 3.4 - Somente o gerente tem acesso a area de fluxo de caixa
    3-> 3.5 - Sistema deve ser capaz de saber qual foi o prato mais pedido no mes, semana e uma determinada data
    3-> 3.5 - Sistema deve ser capaz de saber o quanto um determinado garcom recebeu de gorjeta (10%) em um determinado dia
    
4 - Conta - Fechamento da Mesa
     4-> 4.5 - Sistema deve ser capaz de incluir os 10% do garcom  sobre o total da mesa
 

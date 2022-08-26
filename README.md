##  Projeto-conceitual-BancodeDados

Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

## ♦️ Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

📌 Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;

📌 Pagamento – Pode ter cadastrado mais de uma forma de pagamento;

📌 Entrega – Possui status e código de rastreio;



## O que foi Refinado no projeto?

[1] Modificação

Na tabela antes nomeada apenas como cliente existia nela duas informações, se ele seria (PF ou PJ) foi realizado uma separação criando:

✔️ 2 tabelas cada uma nomeada como Cliente PF e Cliente PJ, sendo assim separando as duas informações.

✔️ Crianção da tabela Login Cliente relacionada com as duas novas tabelas, para que haja uma identificação.
##

[2] Modificação

✔️ Criei a tabela Formas de pagamento e foi acrescentado 3 formas de pagamento (Boleto, Cartão de crédito e Pix).
##
[3] Modificação

✔️ Criei a tabela de Status de pedido com relacionamento com a tabela Formas de pagamento e Pedidos.

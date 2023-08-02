# Modelagem_Ecommerce

O projeto de modelagem de um ecommerce no modelo Entidade-Relacionamento ou Entidade-Relacionamento Estendido foi criado para a "Formação SQL Database Specialist" ofertado pela DIO. 

As narrativas foram as seguintes:

*Narrativa - Produto*

Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros)

Cada produto possui um fornecedor

Um ou mais produtos podem compor um pedido

*Narrativa - Cliente*
O cliente pode se cadastrar no site com seu CPF ou CNPJ

O Endereço do cliente irá determinar o valor do frete

Um cliente pode comprar mais de um pedido. 

Este tem um período de carência para devolução do produto

*Narrativa – Pedido*
O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega

Um produto ou mais compoem o pedido

O pedido pode ser cancelado

A partir dessas narrativas, o desafio foi resolver as questões abaixo e complementar o modelo com o que mais fosse necessário: 

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento
* Entrega – Possui status e código de rastreio

Diante disso, a minha solução é a proposta na imagem abaixo. O desenvolvimento da modelagem foi feita utilizando a ferramenta MySQL Workbench.

C:\Users\Rafael\OneDrive\10 - DIO\2 - Formação SQL Database Specialist\Modelo Ecommerce.png

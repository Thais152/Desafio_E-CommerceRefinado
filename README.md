# Desafio E-Commerce refinamento | Treinamento DIO

A partir do projeto conceitual ensinado, foi feito um refinamento incluindo algumas entidades e atributos sobre o levantamento de requisitos do cliente PJ e PF, pagamento e entrega.

## 📜📜📜 Explicando o refinamento do diagrama
- ### Cliente PJ e PF: 
A partir da entidade cliente, foi realizado uma especialização para os dois tipos de clientes, pessoa física e pessoa jurídica. Dessa forma, um mesmo cliente pode ter contas diferentes como PF ou PJ. 
- ### Pagamento: 
Foi criada uma nova entidade pagamento com relação de (n:m) com a entidade cliente, pois um cliente pode ter várias formas de pagamento cadastradas e uma forma de pagamento pode ser usada por vários clientes. A partir disso, houve uma especialização da forma de pagamento para boleto, pix, dinheiro e cartão de crédito, porque cada um desses tipos tem dados importantes a serem armazenados em um e-commerce. 
- ### Entrega: 
Entrega se transformou em uma nova entidade que tem conexão de (1:n) com a entidade pedido. Assim, um pedido pode ser enviado em uma ou mais entregas, mas uma entrega está relacionada a apenas um pedido. 

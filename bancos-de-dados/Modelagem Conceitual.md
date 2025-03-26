A ~={pink}modelagem conceitual=~ é uma técnica aplica para construir o estágio inicial de um banco de dados. É onde definimos as entidades, os atributos e os relacionamentos entre cada entidade. A cardinalidade é outro conceito aplicado visando melhorar a manutenção, desempenho das consultas, integridade dos dados e etc... 
Exemplo: **(1, n)** -> está associada a **pelo menos 1 e no máximo n** instâncias dessa entidade. Lê-se "~={orange}~={pink}~={cyan}um para muitos=~=~=~".
É usado para indicar que uma ocorrência de uma entidade está associada a **no mínimo uma e no máximo várias** ocorrências da outra entidade. Considere o relacionamento entre as entidades **"Cliente"** e **"Pedido"**:

Um **Cliente** pode fazer **vários Pedidos**.
Cada **Pedido** está associado a **um Cliente**.
- 
Neste caso, a cardinalidade entre **Cliente e Pedido** pode ser descrita como:
Lado do **Cliente**: **(1, n)** → Um cliente faz **de 1 a muitos pedidos**.
Lado do **Pedido**: **(1, 1)** → Um pedido está ligado a **exatamente um cliente**.

![[conceptual_modeling.png]]

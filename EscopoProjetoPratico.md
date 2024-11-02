## Este sistema foi desenvolvido se baseando na necessidade da criação de um banco de dados que realiza vendas e armazena produtos em depósitos, fornecendo um controle centralizado de clientes, vendedores, peças e pedidos. O objetivo é criar um banco de dados simples que permita registrar e organizar todas as operações de vendas, desde o pedido de uma peça até a entrega ao cliente final.
</br>

# Exemplo de escopo e funcionalidades principais


1.	Cadastro de Clientes
Cada cliente possui um identificador único, juntamente com nome e endereço, armazenados na tabela CLIENTE. Isso permite que a empresa mantenha informações atualizadas e precisas para cada um de seus clientes.
</br>

3.	Gestão de Peças e Depósitos
As peças são itens que a empresa armazena e vende. A tabela PEÇA registra informações como descrição, preço cotado, preço unitário e quantidade em estoque.
A relação entre as peças e os depósitos é gerenciada através da tabela DEPÓSITO, que armazena a localização dos depósitos e permite saber em qual depósito cada peça está alocada.
</br>

5.	Controle de Pedidos
	A tabela PEDIDO é usada para registrar todos os pedidos realizados pelos clientes. Cada pedido contém informações sobre a data de realização e o cliente responsável pelo pedido.
	Para gerenciar os itens solicitados em cada pedido, o relacionamento PEDIDO_PEÇA armazena os detalhes de cada peça incluída no pedido, incluindo a quantidade de unidades solicitadas.
</br>

7.	Informações de Vendedores e Comissão
	A tabela VENDEDOR armazena informações sobre cada vendedor, incluindo o nome e o percentual de comissão sobre vendas realizadas. Isso permite à empresa calcular comissões de maneira eficiente e justa.
	O relacionamento Relacao1_CLIENTE1, Relacao1_PEDIDO1 e Relacao1_VENDEDOR1 define uma conexão entre clientes, pedidos e vendedores, indicando qual vendedor é responsável por cada cliente e pedido, facilitando o acompanhamento das vendas por funcionário.
</br>

9.	Relatórios e Análises
	Com base nesses dados, o sistema poderá gerar relatórios detalhados que auxiliem na tomada de decisões. Por exemplo, pode-se identificar os clientes mais frequentes, acompanhar a performance de cada vendedor, verificar quais peças estão em alta demanda e monitorar o nível de estoque em cada depósito.




# Modelo conceitual:
![1s](https://github.com/user-attachments/assets/e621904b-b5b2-4a05-9ac6-e9f1546727f4)
![2s](https://github.com/user-attachments/assets/39f0b6c9-dcc0-412e-bce8-6ddfe47a57ed)

# Modelo Lógico:
![1l](https://github.com/user-attachments/assets/9a0bf1c7-ccb8-4431-a9bb-c029e1a11176)
![2l](https://github.com/user-attachments/assets/4e53ac8b-76b4-4fc5-82f8-7290e0ab7616)




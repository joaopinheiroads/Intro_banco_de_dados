


# Projeto de Desenvolvimento de Banco de Dados
<br/>

## Etapas do Desenvolvimento de um Banco de Dados
<br/>

### Todo projeto de banco de dados bem-sucedido deve seguir um processo estruturado, respeitando as seguintes etapas: 
Levantamento de Requisitos <br/>
Modelagem Conceitual <br/>
Modelagem Lógica <br/>
Modelagem Física <br/>




### Introdução à Modelagem Conceitual:
 A modelagem conceitual é o primeiro passo no projeto de um banco de dados. Pense nela como a planta de uma casa: essencial para garantir que tudo seja construído de maneira sólida. Nesse nível, não nos preocupamos com aspectos técnicos, mas sim com a representação do mundo real no sistema. O foco aqui é como o negócio funciona e como ele será refletido no banco de dados.

### Principais Componentes da Modelagem Conceitual:
### Entidades
São representações de objetos do mundo real. Uma entidade pode ser algo tangível ou conceitual.
Exemplo: Em um sistema de biblioteca, temos as entidades "Livros", "Usuários" e "Funcionários".

### Atributos
São as características ou propriedades de uma entidade.
Exemplo: A entidade "Livro" pode ter os atributos "Título", "Autor" e "Gênero".

### Métodos
Representam as ações ou estados que uma entidade pode ter no sistema.
Exemplo: A entidade "Livro" pode ter métodos como "Emprestado" ou "Devolvido".

<br>

### Exemplo Prático:
Vamos imaginar um banco de dados para uma biblioteca. Durante a modelagem conceitual, identificamos as seguintes entidades e atributos:

Entidade: Livro
Atributos: Título, Autor, Gênero, Data de Publicação
Métodos: Emprestado, Devolvido

Entidade: Usuário
Atributos: Nome, ID de Usuário, Data de Cadastro
Métodos: Realizar Empréstimo, Devolver Livro

<br>
Observação Importante:
É fundamental lembrar que essas definições de entidades, atributos e métodos vêm de um processo anterior chamado levantamento de requisitos, onde são identificadas as necessidades do sistema.
Por exemplo, para decidir que precisamos de uma entidade "Livro" com os atributos "Nome" e "Gênero", essas necessidades foram discutidas e aprovadas na fase de requisitos, como: "Precisamos que o banco de dados armazene informações sobre livros, seus títulos, autores, etc."


# Programa para desenvolvor os conceitos de modelagem(BRmodelo):

Apliquei conceitos de entidades, relação e cardinalidade.

Obs: na etapa de modelagem conceitual, devemos semprer colocar a cardinalidade máxima como "n", pois é na modelagem lógica que definimos a cardinalidade máxima.


![Brmodelo](https://github.com/user-attachments/assets/8ff1b7d4-d8a4-4eac-8e32-a59aebec1225)



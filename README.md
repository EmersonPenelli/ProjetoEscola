# ProjetoEscola
# Desenvolvimento

## Instruções do projeto
De acordo com os comandos aprendidos, programe códigos SQL para criar um banco de dados chamado ESCOLA e deixe-o pronto para o uso. Depois, pesquise qual é o comando utilizado para inserir uma tabela no banco de dados e siga as instruções:

crie uma tabela chamada ALUNO;
defina os atributos da tabela;
adicione a chave primária de nome ID (identificador);
adicione um atributo nome do tipo varchar;
adicione um atributo e-mail do tipo varchar;
adicione um atributo endereço do tipo varchar.


## Resposta


CREATE TABLE aluno (  <br /> 
  ID SERIAL PRIMARY KEY,  <br />
  nome VARCHAR(30) NOT NULL,  <br /> 
  email VARCHAR(50),  <br /> 
  endereco VARCHAR(100) <br /> 
  );

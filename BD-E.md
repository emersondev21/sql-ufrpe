# Aula Prática de SQL
___
### Primeira tabela
```
CREATE TABLE Primeira_tabela (
  Clienteid int,
  Nome varchar(50) not null,
  Endereco varchar(50) not null,
  Cidade varchar(25) not null,
  Estado char(2) not null,
  primary key (Clienteid)
)
```
___
### (slide 16)
```
CREATE TABLE Clientes (
  Clienteid int AUTO_INCREMENT,
  Nome varchar(100) not null,
  Email varchar(150) NOT NULL,
  DataNascimento DATE NOT NULL,
  primary key (Clienteid)
)
```
___
### (slide 17)
```
CREATE TABLE Produtos (
  ProdutoID int AUTO_INCREMENT,
  NomeProduto varchar(200) not null,
  Preco decimal NOT NULL,
  primary key (ProdutoID)
)
```
___
### (slide 17)
```
CREATE TABLE Funcionarios (
  FuncionarioID int AUTO_INCREMENT,
  Nome varchar(100) not null,
  Cargo varchar(50),
  Salario decimal NOT NULL,
  DataContratacao DATE,
  primary key (FuncionarioID)
)
```
___
### (Slide 18)
```
CREATE TABLE Fornecedores (
  FornecedorID int AUTO_INCREMENT,
  NomeFornecedor varchar(150) not null,
  Telefone varchar(20) UNIQUE,
  Endereco varchar(250),
  primary key (FornecedorID)
)
```
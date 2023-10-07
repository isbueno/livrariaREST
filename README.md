# appREST
API CRUD RESTful para o gerenciamento de uma tabela relacional simples.

O objetivo final é conseguir ler uma tabela "Livro" em MySql fazendo uso de uma ORM Sequelize. Para montar a aplicação, foram usados Node.js e Express.js.

---

## Instalação



---

### Tabela Livro

![image](https://github.com/isbueno/appREST/assets/102770607/87a85cc2-3a65-489a-86f8-f5e0995a7b6c)
Legenda: Tabela Livro no diagrama de Classe.

A tabela mapeada serve para representar um produto de e-commerce. Ainda não foram adicionadas outras tabelas que poderiam se relacionar com "Livro", já que o objetivo é somente mapear uma única tabela. 

Os atributos de Livro são:
* ID do Livro
* Nome
* Autor
* Genero
* Editora
* Preço
* Sku
* Quantidade de Páginas
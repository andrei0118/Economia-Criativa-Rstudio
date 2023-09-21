# Estudo sobre Economia Criativa em Santo Antônio do Leite - MG

## Licença  
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/andrei0118/gn-vendas/blob/master/LICENSE)

## Sobre o projeto
GN-VENDAS é uma api.rest construída durante o processo de seleção da empresa GERENCIANET. A aplicação consiste em um sistema de vendas online, onde  o administrador poderá  cadastrar  produtos de uma loja,  e seu cliente final poderá comprar e gerar o boleto de pagamento  do item desejado.
É possível dividir o projeto em 3 partes:

# Como executar o projeto

- Instalar as dependencias do nodejs e express.
- Instalar o simulador de servidor Xampp.
- Foi utilizado o banco de dados Mysql, sendo mysqladmin: (Usuário= "root") (senha " ").
- Abra seu terminal e digite npm start para iniciar aplicação.
- Página para cadastro de produtos: http://localhost:5000/cadastro , nesta página o administrador poderá cadastrar , editar ou mesmo deletar produtos de sua loja.
- Página de listagem (loja) de produtos: http://localhost:5000/lojaprodutos/ , nesta página o cliente poderá visualizar todos produtos cadastrados na loja e assim compra - los.
- Pagina de comprar e gerar boleto: http://localhost:5000/gerarboleto/:id , nesta página o cliente irá colocar seu dados sendo: Nome, CPF e telefone e assim gerar o boleto para efetivar a compra.




## Autor
Andrei Camilo dos Santos
https://www.linkedin.com/in/andrei0118-santos

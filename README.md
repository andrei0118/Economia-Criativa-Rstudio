# Pesquisa sobre Economia Criativa em Santo Antônio do Leite - MG

## Licença  
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/andrei0118/gn-vendas/blob/master/LICENSE)

## Sobre o projeto
GN-VENDAS é uma api.rest construída durante o processo de seleção da empresa GERENCIANET. A aplicação consiste em um sistema de vendas online, onde  o administrador poderá  cadastrar  produtos de uma loja,  e seu cliente final poderá comprar e gerar o boleto de pagamento  do item desejado.
É possível dividir o projeto em 3 partes:

![Relatorio-Economia-Criativa-01](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/80366e2a-22c9-41aa-938a-931c297e8df7)
![Relatorio-Economia-Criativa-02](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/5ff87626-cfff-4d99-9664-f44139beaaa4)
![Relatorio-Economia-Criativa-03](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/41b33b86-9324-4a42-aa48-375db6091e8e)
![Relatorio-Economia-Criativa-04](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/c848c65e-e5e7-4482-8541-e57733982e4d)
![Relatorio-Economia-Criativa-05](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/3a35d00a-8aa3-4596-9906-9b842cb7f075)
![Relatorio-Economia-Criativa-06](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/44d1d831-7e8d-43fe-9d4f-f519097c817c)
![Relatorio-Economia-Criativa-07](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/bbf2d2cb-8bc9-4176-aa21-23af4d3f33bc)
![Relatorio-Economia-Criativa-08](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/50fbdd0f-15f9-4ceb-b9f0-9d2e38baab03)
![Relatorio-Economia-Criativa-09](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/7faeb2ce-cdc0-4e1f-93dd-fa4fcfe803f6)
![Relatorio-Economia-Criativa-10](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/2c0f9cbb-3038-4d87-91c3-890d2cb82d86)
![Relatorio-Economia-Criativa-11](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/314c7017-ecc6-4633-a75e-33b58bd66e09)
![Relatorio-Economia-Criativa-12](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/9614362e-f5ce-402e-b2cc-81cb644331a8)
![Relatorio-Economia-Criativa-13](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/6bb4cc08-644f-4b61-8e4e-76e1faf32827)
![Relatorio-Economia-Criativa-14](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/f05de440-38b3-42da-8701-e6129f34229e)
![Relatorio-Economia-Criativa-15](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/e945bdbe-6665-4feb-ac39-9e7dfbefc5b9)
![Relatorio-Economia-Criativa-16](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/4e5a5f34-900c-4653-b8e4-038cc724dde9)
![Relatorio-Economia-Criativa-17](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/07774865-b339-4433-807c-c602a1598e6c)
![Relatorio-Economia-Criativa-18](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/ff7a3509-6acd-419d-80f9-1988fc271d79)
![Relatorio-Economia-Criativa-19](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/67ab4e41-dc09-4b0a-a303-a59cab26f2a4)
![Relatorio-Economia-Criativa-20](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/98c0cffd-5d6b-4f07-92ee-00ffeb77bce4)
![Relatorio-Economia-Criativa-21](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/de789a57-77a9-42ba-83d1-d0c05c6bd04b)
![Relatorio-Economia-Criativa-22](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/9f31d717-53c9-4bcc-87de-6e152f607892)
![Relatorio-Economia-Criativa-23](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/337a868d-a230-414a-9abc-90629ce2fbac)
![Relatorio-Economia-Criativa-24](https://github.com/andrei0118/Economia-Criativa-Rstudio/assets/75299828/c03e86aa-f767-48a9-bdb3-aff7c2edaad1)


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

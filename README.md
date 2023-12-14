<h1 align="center"> 
	Sistema PDV (Frente de caixa) 💻
</h1>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-linguagem-utilizada">Tecnologias</a> • 
   <a href="#-pre-requisitos">Desenvolvedoras</a> • 
</p>

## 💻 Sobre o projeto

Este projeto foi a criação de uma API para uma frente de caixa (PDV), feito como desafio do Modulo V do curso de desenvolvimento de software com foco em Back-end da **Cubos Academy** em parceria com a **Ifood**. Esse será um projeto **piloto**, ou seja, no futuro outras funcionalidades serão implementadas, este projeto foi realizado em equipe, formada por cinco mulheres, **Marcela**, **Karolayne**, **Bruna**, **Thais** e **Debora**.

E foi dividido em três sprints:

<details>
<summary>1ª Sprint</summary>
<br>

- **Banco de Dados:**
Criação tabelas e colunas para **usuarios** e **categorias**.

- **Listar categorias:**
Essa é a rota que será chamada quando o usuário quiser listar todas as categorias cadastradas.

- **Cadastrar usuário:**
Essa é a rota que será utilizada para cadastrar um novo usuário no sistema.

- **Efetuar login do usuário:**
Essa é a rota que permite o usuário cadastrado realizar o login no sistema.

- **Detalhar perfil do usuário logado:**
Essa é a rota que permite o usuário logado a visualizar os dados do seu próprio perfil, de acordo com a validação do token de autenticação.

- **Editar perfil do usuário logado:**
Essa é a rota que permite o usuário logado atualizar informações de seu próprio cadastro, de acordo com a validação do token de autenticação.

- **Efetuar deploy da aplicação:**
Fizemos o deploy do projeto, pelo site da Cyclic. Em "como executar o projeto" você encontrará o link do deploy.

</details>

---

<details>
<summary>2ª Sprint</summary>
<br>

- **Cadastrar Produto:**
Essa é a rota que permite o usuário logado cadastrar um novo produto no sistema.

- **Editar dados do produto:**
Essa é a rota que permite o usuário logado a atualizar as informações de um produto cadastrado.

- **Listar Produtos:**
Essa é a rota que será chamada quando o usuário logado quiser listar todos os produtos cadastrados.

- **Detalhar Produto:**
Essa é a rota que permite o usuário logado obter um de seus produtos cadastrados.

- **Excluir Produto por ID:**
Essa é a rota que será chamada quando o usuário logado quiser excluir um de seus produtos cadastrados.

- **Cadastrar Cliente:**
Essa é a rota que permite usuário logado cadastrar um novo cliente no sistema.

- **Editar dados do cliente:**
Essa é a rota que permite o usuário realizar atualização de um cliente cadastrado.

- **Listar Clientes:**
Essa é a rota que será chamada quando o usuário logado quiser listar todos os clientes cadastrados.

- **Detalhar Cliente:**
Essa é a rota que será chamada quando o usuário logado quiser obter um de seus clientes cadastrados.

</details>

---

<details>
<summary>3ª Sprint</summary>
<br>

- **Cadastrar Pedido:**
Essa é a rota que será utilizada para cadastrar um novo pedido no sistema. E após o pedido cadastrado é enviado um e-mail para o cliente notificando que o pedido foi efetuado com sucesso. 

- **Listar Pedidos:**
Essa é a rota que será chamada quando o usuário logado quiser listar todos os pedidos cadastrados.

- **Aplicar validação na exclusão de produto:**
Foi aplicada uma regra de negócio que não permitirá exclusão de produto que tenha sido registrado em algum pedido.

- **Aprimorar cadastro/atualização de produto:**
Foram aprimorados o cadastro e a atualização de produto para permitir vincular uma imagem a um produto. 

- **Aprimorar exclusão de produto:**
Foi aprimorada a exclusão de produto para que quando o produto for excluído também seja removida a imagem vinculada a ele na servidor de armazenamento.

</details>

---
<h1 align="center"> 
	Sistema PDV (Frente de caixa) 💻
</h1>

<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-como-executar-o-projeto">Como executar</a> • 
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

## ✅ Como executar o projeto

 Abaixo segue as principais instruções para execução do projeto:

<details>
<summary>1.Requisitos Prévios</summary>
<br>

Para que seja realizado requisições com os verbos POST, PUT, DELETE use a extensão Thunder Client do VSCode, o aplicativo Insomnia ou similar.

- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/)
- [VSCode](https://code.visualstudio.com/)
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [Insomnia](https://insomnia.rest/download)

</details>

---

<details>
<summary>2.Clone o Repositório</summary>
<br>

**Passo 1: Obtenha o URL do Repositório**
- https://github.com/KarolayneADP/SistemaPDV

**Passo 2: Abra o Terminal ou Prompt de Comando e Clone o repositório**
- Vá ate á URL do repositório e clique no canto superior direito em **Code**.
- Selecione a chave de sua preferência e dê o comando git clone.
- Pressione Enter para executar o comando. O Git irá baixar todos os arquivos do repositório para o diretório atual.

</details>

---

<details>
<summary>3.Instale Dependências</summary>
<br>

No seu terminal digite o comando **npm install** para instalar todas as dependências do projeto.

</details>

---

<details>
<summary>4.Execução</summary>
<br>

- O Projeto pode ser inicializado localmente atravéz do comando **npm start**.
- A API estará disponível em http://localhost:3000.
- A API estará disponivel, por tempo limitado, atravéz do link do deploy do projeto https://pdv-equipe-codein5.cyclic.app/.

</details>

---

<details>
<summary>5.Problemas Conhecidos</summary>
<br>

 - Se encontrar problemas com a conexão com o banco de dados, verifique as configurações no arquivo .env.

**Informações para Complementar arquivo .env.:**

kEY_ID= 005f88682bf09180000000001<br>
kEY_NAME= equipeCodeIn5<br>
APP_KEY= K005wmjWoBzXPgMwtv7OEFRlhM9XOSo<br>
ENDPOINT_S3= s3.us-east-005.backblazeb2.com<br>
BACKBLAZE_BACKET = equipeCodeIn5<br>

EMAIL_HOST=smtp.sendgrid.net<br>
EMAIL_PORT=465<br>
EMAIL_USER=apikey<br>
EMAIL_PASS="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"<br>
EMAIL_NAME="PDV-Equipe-CodeIn5"<br>
EMAIL_FROM=pdv.equipecodein5@gmail.com

</details>

---

## Desenvolvedoras do Projeto:

| [<img src="![Alt text](Karolayne.jpg)" width=50><br><sub>Karolayne Arantes</sub>](https://www.linkedin.com/in/karolayne-arantes/) |
| :---: | | [<img src="![Alt text](Marcela.jpg)" width=50><br><sub>Marcela Linhares</sub>](https://www.linkedin.com/in/marcelagabilan/) |
| :---: |

| [<img src="![Alt text](Debora.jpg)" width=50><br><sub>Débora Francislayne</sub>](https://www.linkedin.com/in/debora-francislayne-silva1/) |
| :---: |

| [<img src="![Alt text](Bruna.jpg)" width=50><br><sub>Bruna Rodrigues</sub>](https://www.linkedin.com/in/brunarodferreira/) |
| :---: |

| [<img src="![Alt text](Thais.jpg)" width=50><br><sub>Thaís Paixão</sub>](https://www.linkedin.com/in/tha%C3%ADs-paix%C3%A3o-742932141/) |
| :---: |

###### tags: `back-end` `nodeJS` `PostgreSQL` `API REST` 
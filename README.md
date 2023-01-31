# TG Aplicativo para venda de tecnologias assitivas

![Badge](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Badge](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=Expo&logoColor=white) ![Badge](https://img.shields.io/badge/NodeJS-339933?style=for-the-badge&logo=Node.js&logoColor=white) ![Badge](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white)


<h1 align="center">
    <img alt="React RocketShoes" src="/documents/tgfinalmesmo_AdobeExpress.gif" />
    <br>
</h1>

## :checkered_flag: Índice

1. [Descrição](#descrição)
2. [Arquitetura](#Arquitetura)
3. [Modelo de Dados](#Dados)

## :books: Descrição <a name="descrição"></a>

<p align="justify">
Este trabalho de graduação é uma aplicação para dispositivos móveis visando conectar pessoas que querem vender, trocar ou doar seus equipamentos ou
serviços de tecnologia assistiva a pessoas que precisam.
</p>

## :bookmark_tabs: Arquitetura <a name="Arquitetura"></a>
• Usuário logado: Anunciante que realizará a criação e edição de anúncios de tecnologias assistivas.
• Usuário não logado: Comprador, usuário que está em busca de tecnologias assistivas e visualizará os anúncios.
• Administrador: Tem a capacidade de criar categorias para setorizar as tecnologias assistivas, além de prestar assistência aos usuários e resolver eventuais problemas da aplicação.
![](/documents/Diagrama_em_branco.png)

## :bookmark_tabs: Modelo de Dados <a name="Dados"></a>
• Category: Armazena os dados das categorias.
• Item: Armazena os dados da relação do anúncio com o anunciante utilizando a chave estrangeira CLI_ID e os dados da relação da categoria com o item com a chave
estrangeira CAT_ID. Além dos dados relativos ao anúncio, como título, preço e descrição etc.
• Client: Armazena os dados do cliente.
![](/documents/bd.png)

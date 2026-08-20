# 🍹 BARBARIDADE

![Status do Projeto](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Techs](https://img.shields.io/badge/Techs-C%23%20%7C%20ASP.NET%20Core%20%7C%20Entity%20Framework%20%7C%20SQLite-orange)

O **BarBaridade** é um sistema desenvolvido em C# com ASP.NET Core que simula uma API para gerenciamento de bebidas e seus respectivos teores alcoólicos. O projeto implementa operações de cadastro, consulta, atualização e exclusão de bebidas, utilizando Entity Framework Core para integração com banco de dados SQLite.

---

## 🚀 Funcionalidades

* **Listagem de Bebidas:** Consulta todas as bebidas cadastradas no banco de dados.
* **Busca por ID:** Consulta individual de uma bebida.
* **Cadastro:** Adição de novas bebidas ao catálogo.
* **Atualização:** Alteração do nome e teor alcoólico.
* **Exclusão:** Remoção de bebidas do catálogo.
* **Persistência de Dados:** Armazenamento utilizando SQLite.
* **API REST:** Endpoints para comunicação com o front-end.
* **Interface Web:** Visualização e interação com as bebidas cadastradas.

## 🛠️ Tecnologias Utilizadas

* **C#:** Desenvolvimento da aplicação e regras de negócio.
* **ASP.NET Core:** Construção da API REST.
* **Entity Framework Core:** Acesso e gerenciamento do banco de dados.
* **SQLite:** Persistência dos dados.
* **HTML, CSS e JavaScript:** Desenvolvimento da interface web.
* **Swagger:** Documentação e testes da API.

## 💻 Como Rodar o Projeto Localmente

### Pré-requisitos

* **Git**
* **.NET SDK**
* **Visual Studio Code**

### Passo a Passo

1. Clone o repositório e abra a pasta no VS Code:

   ```bash
   git clone https://github.com/Ana-Maria-Lange/BARBARIDADE_C-sharp.git
   cd BARBARIDADE_C-sharp
   code .
   ```

2. Execute a API:

   ```bash
   cd src/BarBaridade.Api
   dotnet run
   ```

3. Abra `src/BarBaridade.Web/index.html` no navegador ou utilize o **Live Server** do VS Code.

> **Nota:** O banco de dados SQLite com registros de exemplo está incluído no repositório, portanto não é necessário executar migrations para iniciar o projeto. As migrations do Entity Framework Core estão disponíveis na pasta `Migrations` para controle da estrutura do banco.

# 🎉 Projeto de API de Gestão de Pessoas

Este projeto é uma **API** desenvolvida em **C#** utilizando o **ASP.NET Core**, que permite a gestão de pessoas, incluindo funcionalidades para criar, ler, atualizar e excluir registros de pessoas. 🧑‍🤝‍🧑

## 🗂 Estrutura do Projeto

- **Domain** 📁
  - Contém as entidades e interfaces do domínio.
  
- **Infra** 🔧
  - Implementação do contexto do banco de dados e dos repositórios.
  - Configuração da migração do banco de dados.

- **Server.Facul.API** 🌐
  - Controllers que gerenciam as requisições HTTP.

- **wwwroot** 📂
  - Arquivos estáticos, como HTML, CSS e JavaScript.

## 🚀 Funcionalidades da API

- **GET** `/api/Pessoa` 📜: Retorna todos os registros de pessoas.
- **POST** `/api/Pessoa/Gravar` ➕: Adiciona um novo registro de pessoa.
- **PUT** `/api/Pessoa/Alterar` ✏️: Atualiza um registro existente de pessoa.
- **DELETE** `/api/Pessoa/Delete/{id}` ❌: Remove um registro de pessoa pelo ID.

## ⚙️ Configuração do Banco de Dados

O projeto utiliza o **MySQL** como banco de dados. Certifique-se de ter uma instância do MySQL rodando e configure a string de conexão no arquivo `appsettings.json`:

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "server=localhost;database=SeuBancoDeDados;user=seuUsuario;password=suaSenha"
  }
}
```

## 🖥 Frontend
O frontend da aplicação é desenvolvido em HTML, CSS e JavaScript, permitindo a interação com a API. O código JavaScript realiza as operações CRUD e atualiza a interface do usuário com os dados retornados pela API. 💻✨

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests. 🌟

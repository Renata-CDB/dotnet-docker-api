# dotnet-docker-api
# TaskApi (.NET 8 + Web API + Swagger)

Este projeto é uma API REST desenvolvida em **.NET 8** utilizando o modelo `webapi`.  
Foi criada e executada diretamente no **GitHub Codespaces**, sem necessidade de instalação local de SDKs ou Docker.

## 🚀 Tecnologias
- .NET 8 (ASP.NET Core Web API)
- Entity Framework Core (InMemory)
- Swagger / OpenAPI
- GitHub Codespaces

## ⚡ Como rodar no GitHub Codespaces

1. Abra este repositório no GitHub.  
2. Clique em **Code** → **Codespaces** → **Create codespace on main**.  
   - 📖 [Quickstart: GitHub Codespaces](https://docs.github.com/en/codespaces/getting-started/quickstart)  
3. O Codespaces abrirá um VS Code online com terminal integrado.  
4. No terminal, rode os comandos:

```bash
dotnet new webapi --use-controllers -n TaskApi
cd TaskApi
dotnet run

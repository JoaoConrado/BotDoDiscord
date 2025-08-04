# BotDoDiscord

Este repositório contém o código de um bot para **Discord**, desenvolvido em **C#** como parte do curso de AED (Algoritmos e Estruturas de Dados). O projeto foi criado com o objetivo de testar e aplicar conhecimentos em programação orientada a objetos e na API do Discord.

## 🚀 Funcionalidades Principais

* **Comandos Personalizados:** O bot é capaz de responder a comandos específicos. A lógica desses comandos está organizada de forma modular para facilitar a adição de novas funcionalidades.
* **Interação com Usuários:** O bot pode interagir com os membros do servidor, respondendo a mensagens e executando tarefas simples.
* **Aprendizado de C#:** Este projeto serve como um ótimo exemplo de como usar a linguagem **C#** para construir aplicações práticas, como bots.

## 🧠 Estrutura do Projeto

O código do bot está organizado de maneira clara e lógica.

* `Program.cs`: Este é o arquivo principal, onde a lógica de inicialização do bot e a conexão com o Discord são gerenciadas.
* `Comandos/`: Esta pasta contém a lógica para cada comando que o bot pode executar, o que torna o código mais fácil de gerenciar e expandir.
* `Discord.app.csproj`: Arquivo de projeto do C#, que define as configurações e dependências do seu bot.
* `Discord.app.sln`: O arquivo de solução do Visual Studio, que organiza o projeto e os seus arquivos.

## 🛠️ Como Executar

Para executar o bot, você precisará do **.NET SDK** e de um token de bot do Discord.

1.  **Pré-requisitos:** Certifique-se de ter o [.NET SDK](https://dotnet.microsoft.com/download) instalado.
2.  **Obter o Token:** Crie um aplicativo de bot no [Portal de Desenvolvedores do Discord](https://discord.com/developers/applications) e obtenha o token de autenticação.
3.  **Configurar o Token:** Insira o seu token no código (normalmente em uma variável de ambiente ou em um arquivo de configuração).
4.  **Compilar e Rodar:**
    ```bash
    dotnet run
    ```
---

### Integrantes

- **RM98641** - Guilherme Henrique Almeida Jeronimo  
- **RM99959** - Gustavo Henrique Furtado Lourenço  
- **RM550806** - Iago Martins Carapiá Uttemberg  
- **RM550878** - Matheus da Costa Gonçalves  
- **RM99347** - Thomas Jeferson Santana Wang  

### Vídeo do projeto:
https://www.youtube.com/watch?v=rOOvjSZkL44

---

### Ideia do Projeto

O projeto consiste em desenvolver um chatbot utilizando o modelo generativo **"Gemini 1.5 Pro"** da Google Generative AI, que atua como um assistente virtual para suporte ao cliente da empresa Plusoft. A IA é configurada para responder de maneira personalizada e segura, lidando com grandes volumes de consultas e ajustando seu comportamento de acordo com instruções específicas. A implementação inclui a configuração da API, a definição de parâmetros de geração e segurança, e um sistema de chat dinâmico para interação contínua com os usuários.

### Arquitetura da IA

A arquitetura da IA utilizada é o modelo generativo **"Gemini 1.5 Pro"** da **Google Generative AI**, escolhido por sua **escalabilidade**, **personalização** e **segurança**. Ele é adequado para **chatbots** e **assistentes virtuais**, lidando com grandes volumes de consultas e ajustando seu comportamento conforme as instruções específicas, como no caso de um assistente de suporte da Plusoft.

### Implementação

- **Configuração da API**: A API da Google Generative AI é configurada utilizando uma chave de autenticação (`api_key`).
- **Modelo de Geração**: A classe `GenerativeModel` é usada para definir parâmetros de geração e segurança.
- **Chat Dinâmico**: Um loop `while` gerencia a interação do usuário, processando o input até a finalização.

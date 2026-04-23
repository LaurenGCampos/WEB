📚 Resumo – Introdução a Frameworks Back-end

🌐 1. O que são Frameworks Back-end

Frameworks back-end são conjuntos de ferramentas que ajudam a desenvolver a parte do servidor de aplicações web.

🔹 Funções principais:
Organizar código
Criar APIs
Integrar com banco de dados
Garantir segurança e escalabilidade

🔹 Sem framework:
Mais código manual
Maior risco de erros
Dificuldade de manutenção

🔹 Com framework:
Código organizado
Mais segurança
Facilidade para crescer o sistema

🏗️ 2. Arquitetura e Organização

Frameworks utilizam padrões para organizar o sistema.

🔹 MVC:
Model: dados
View: interface
Controller: lógica

🔹 Vantagens:
Separação de responsabilidades
Facilidade de manutenção
Código mais limpo

🧩 3. Design Patterns

São padrões reutilizáveis para resolver problemas comuns no desenvolvimento.

🔹 Tipos:
Criacionais: criação de objetos
Estruturais: organização do sistema
Comportamentais: comunicação entre partes

⚙️ 4. Características dos Frameworks

Código modular (componentes e serviços)
Suporte a programação assíncrona
Sistema de rotas para APIs
Segurança integrada (ex: proteção contra ataques)
Facilidade para criar e gerenciar endpoints

🆚 5. Monolito vs Microsserviços

Monolito:
Aplicação única
Mais simples de desenvolver
Difícil de escalar

Microsserviços:
Sistema dividido em partes independentes
Mais escalável
Mais complexo de gerenciar

A escolha depende do tamanho do projeto e da equipe

🧪 6. Exemplos de Frameworks

Express.js: leve e flexível (Node.js)
Django: completo e robusto (Python)
Laravel: popular no PHP

🚀 7. Express.js

Framework minimalista para Node.js usado para criar servidores e APIs.

🔹 Características:
Roteamento simples
Uso de middlewares
Alta performance
Fácil de aprender

🔹 Uso comum:
Criação de APIs REST
Back-end de aplicações web

🔄 8. Como funciona uma requisição

1. Usuário acessa o sistema
2. Navegador envia requisição HTTP
3. Servidor processa a requisição
4. Consulta banco de dados ou API
5. Retorna resposta em JSON
6. Front-end atualiza a tela

🌍 9. HTTP

Protocolo de comunicação da web entre cliente e servidor

🔹 Características:
Cliente-servidor
Sem estado (stateless)
Baseado em texto

🔹 Métodos principais:
GET: buscar dados
POST: criar dados
PUT/PATCH: atualizar dados
DELETE: remover dados

🔌 10. API e REST

API permite comunicação entre sistemas

REST é um padrão para criar APIs

🔹 Princípios:
Uso de HTTP
Dados em JSON
Sem estado
Recursos com URLs (endpoints)

📍 11. Endpoints

São URLs que representam recursos da API

Exemplo:
/usuarios → lista usuários
POST /usuarios → cria usuário

🖥️ 12. Backend e Web Service

Backend: processa dados e regras de negócio

Web Service: permite comunicação entre sistemas pela internet

📦 13. JSON

Formato leve de dados usado nas APIs

🔹 Estrutura:
Objeto (chave e valor)
Array (lista de valores)

🛠️ 14. Criando API com Express

Passos básicos:
Criar projeto
Instalar express
Criar arquivo da API
Rodar com node

Também pode usar CORS para permitir acesso entre diferentes origens

☁️ 15. Deploy com Render

Plataforma para hospedar APIs

🔹 Vantagens:
Deploy automático
Integração com GitHub
Escalabilidade
HTTPS gratuito

📝 16. Atividade

Criar uma API com Express que retorne data e hora
Fazer deploy no Render
Criar um frontend que consuma essa API
Separar front e back em repositórios diferentes
Documentar tudo com prints e links

🎯 17. Objetivo da aula

Aprender conceitos de back-end
Criar APIs REST
Entender comunicação cliente-servidor
Utilizar Express.js na prática
Publicar aplicações online

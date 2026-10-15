# Saúde App

Aplicação web mobile-first para acompanhar consultas, medicamentos e vacinas em um só lugar. Ela resolve o problema de esquecer datas e horários de cuidados com a saúde, e é voltada a pessoas que querem organizar seus compromissos de saúde (e os da família) de forma simples e segura.

## Objetivo

Oferecer uma ferramenta simples e acessível pelo celular para registrar e consultar compromissos de saúde, ajudando o usuário a manter consultas, medicamentos e vacinas em dia, com privacidade e segurança dos dados.

## Funcionalidades

* Cadastro e autenticação de usuários
* Gerenciamento de consultas, medicamentos e vacinas (cadastrar, listar, editar e apagar)
* Tela inicial com os compromissos do dia
* Interface responsiva para dispositivos móveis e desktops

## Tecnologias utilizadas

* Front-end: HTML5, CSS3 e JavaScript puro
* Back-end: Node.js e Express
* Banco de dados: PostgreSQL
* Controle de versão: Git e GitHub

## Padrões e decisões técnicas

### Stack

* Interface desenvolvida com abordagem mobile-first.
* JavaScript puro no front-end, sem frameworks inicialmente.
* API e regras de negócio implementadas no back-end com Node.js e Express.
* PostgreSQL para persistência dos dados.

### Segurança

* Senhas armazenadas com hash seguro, utilizando Argon2id ou bcrypt, conforme a implementação adotada.
* Validação de entradas no back-end.
* Autenticação e autorização verificadas no servidor.
* Acesso aos dados limitado ao usuário autenticado.
* Consultas SQL parametrizadas, evitando concatenação de entradas nas instruções.
* Segredos e credenciais armazenados em variáveis de ambiente.
* Arquivo `.env` excluído do controle de versão.
* Arquivo `.env.example` disponibilizado sem credenciais reais.
* Dados fictícios utilizados para demonstração e testes, sem dados reais de saúde.

### Organização do desenvolvimento

* Uma funcionalidade por branch, sempre que adequado.
* Commits pequenos, com mensagens claras e descritivas.
* Dependências selecionadas considerando manutenção, popularidade e segurança.
* Execução de `npm audit` durante a revisão das dependências.
* Testes das funcionalidades antes de cada versão publicada.

## Como executar o projeto

As instruções de instalação, configuração das variáveis de ambiente e inicialização serão adicionadas conforme a estrutura do projeto for implementada.

## Status do projeto

Em desenvolvimento.

## Autor

João Gabriel de Souza Moraes
[GitHub](https://github.com/joaomoraez) · [LinkedIn](https://www.linkedin.com/in/joão-gabriel-ab5705352)

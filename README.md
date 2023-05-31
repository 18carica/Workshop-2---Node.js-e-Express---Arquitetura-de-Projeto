# Workshop-2---Node.js-e-Express---Arquitetura-de-Projeto
Workshop: Node.js e Express - Arquitetura de Projeto - Desafio 2

Você deve desenvolver uma API em TypeScript que permita o registro de usuários e a autenticação deles (pode ser em memória ou em um banco de dados). O sistema deve ser capaz de criar um novo usuário, armazenando seu nome, e-mail e senha. Além disso, deve permitir que o usuário faça login fornecendo suas credenciais.

## Requisitos: 

- Implementar uma classe Singleton que seja responsável por gerenciar a criação e acesso à instância única do sistema de gerenciamento de usuários.
- (OPCIONAL) Criar uma classe de fábrica (Factory) para a criação dos objetos de usuário. Essa classe deve ter um método para criar uma instância de usuário com os dados fornecidos.
- Implementar uma rota na API para o registro de um novo usuário. Essa rota deve receber os dados do usuário (nome, e-mail e senha).
- Implementar uma rota na API para a autenticação de um usuário. Essa rota deve receber o e-mail e a senha do usuário e verificar se as credenciais são válidas, utilizando a instância do sistema de gerenciamento de usuários.
- Utilizar o TypeScript para fornecer tipagem estática ao código, garantindo a segurança e a consistência do sistema.
Boa Sorte!


# Blog com Laravel e Bootstrap 

## Visão Geral do Projecto

Este projecto implmenta um sistema de blog utilizando Laravel como backend e Bootstrap para o front-end. Permite aos usuários criar, editar, excluir posts e comentários, além de oferecer autenticação de usário. 


## Configuração do Ambiente

### Instalação 

1. Clone o repositório: 'Link do repositorio'
2. Instale as dependências do Composer: 'composer install'
3. Copie o arquivo '.env.example' para '.emv' e configure as variáveis de ambiente.
4. Gere a chave de aplicação: 'php artisan key: generate'

### Configuração do Banco de Dados
- Execute as migrações para criar as tabelas necessárias: 'php artisan migrate'

## Estrutura do Projecto
- 'app/': Contém os modelos, controllers e lógica de negócio.
- 'resources/views/': Views do Laravel, utilizando Blade e Bootstrap para p frontend.
- ...

## Funcionalidades Implementadas

### Autenticação de Usuário

- Os usuários podem se registrar, fazer login, recuperar senha.
- Middleware de autenticação protege rotas sensíveis.

### CRUD de Posts e Comentários

- Criação, leitura, atualização e exclusão de posts.
- Gerenciamento de comentários associados a cada post.

## Segurança

- Autenticação via tokens JWT.
- Prevenção de CSRF e XSS.

## Guia de Uso

### Configuração Inicial

- `composer install`
- `php artisan migrate`

### Como Executar o Projeto

- `php artisan serve`
- Acesse `http://localhost:8000` no navegador.

## Skills 

- Laravel, Bootstrap 

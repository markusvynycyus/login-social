# login-social

## Autenticação com OpenID Connect no Spring Boot com Facebook e Instagram

Este projeto demonstra uma aplicação Spring Boot que utiliza OpenID Connect para autenticar usuários com Facebook e Instagram. A aplicação usa Spring Security para gerenciar o fluxo de autenticação e fornece um endpoint de login simples para que os usuários autentiquem com suas contas do Facebook ou Instagram.

## Recursos

- **Autenticação com OpenID Connect**: Integração com Facebook e Instagram para autenticação de usuários.
- **Integração com Spring Security**: Autenticação segura usando o Spring Security.
- **Endpoint de Login Simples**: Facilita a autenticação dos usuários com suas contas de mídia social.
- **Redirecionamento para Páginas de Autorização**: Redireciona os usuários para as páginas de autorização do Facebook e Instagram para autenticação.
- **Gerenciamento de Tokens**: Lida com o código de autorização e troca de token para garantir uma autenticação segura.

## Como Funciona

1. O usuário solicita login com sua conta do Facebook ou Instagram.
2. A aplicação redireciona o usuário para a página de autorização do Facebook ou Instagram.
3. O usuário concede permissão para que a aplicação acesse suas informações de perfil.
4. O Facebook ou Instagram redireciona o usuário de volta para a aplicação com um código de autorização.
5. A aplicação troca o código de autorização por um token de acesso.
6. A aplicação usa o token de acesso para autenticar o usuário e conceder acesso à aplicação.

## Tecnologias Utilizadas

- **Spring Boot**
- **Spring Security**
- **OpenID Connect**
- **API do Facebook**
- **API do Instagram**

## Iniciando

Para executar a aplicação, siga os passos abaixo:

1. Para executar a aplicação, basta clonar o repositório e executar a aplicação Spring Boot. Você precisará configurar as credenciais da API do Facebook e Instagram no arquivo application.properties.
Este projeto é um ponto de partida para construir um sistema de autenticação mais abrangente usando OpenID Connect e plataformas de mídia social.Clone o repositório:
   ```bash
   git clone <url-do-repositorio>

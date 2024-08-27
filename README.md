# login-social

Autenticação com OpenID Connect no Spring Boot com Facebook e Instagram

Este projeto demonstra uma aplicação Spring Boot que utiliza OpenID Connect para autenticar usuários com Facebook e Instagram. A aplicação usa Spring Security para lidar com o fluxo de autenticação e fornece um endpoint de login simples para que os usuários autentiquem com suas contas do Facebook ou Instagram.

Recursos

    Autenticação com OpenID Connect com Facebook e Instagram
    Integração com Spring Security para autenticação segura
    Endpoint de login simples para que os usuários autentiquem com suas contas de mídia social
    Redireciona para as páginas de autorização do Facebook e Instagram para autenticação
    Lida com código de autorização e troca de token para autenticação segura

Como funciona

    O usuário solicita login com sua conta do Facebook ou Instagram.
    A aplicação redireciona o usuário para a página de autorização do Facebook ou Instagram.
    O usuário concede permissão para que a aplicação acesse suas informações de perfil.
    O Facebook ou Instagram redireciona o usuário de volta para a aplicação com um código de autorização.
    A aplicação troca o código de autorização por um token de acesso.
    A aplicação usa o token de acesso para autenticar o usuário e conceder acesso à aplicação.

Tecnologias utilizadas

    Spring Boot
    Spring Security
    OpenID Connect
    API do Facebook
    API do Instagram

Iniciando

Para executar a aplicação, basta clonar o repositório e executar a aplicação Spring Boot. Você precisará configurar as credenciais da API do Facebook e Instagram no arquivo application.properties.

Este projeto é um ponto de partida para construir um sistema de autenticação mais abrangente usando OpenID Connect e plataformas de mídia social.

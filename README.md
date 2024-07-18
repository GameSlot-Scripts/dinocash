
# DinoCash - Sistema de Apostas Online

Bem-vindo ao repositório do DinoCash, um sistema de apostas online robusto e seguro desenvolvido com as mais recentes tecnologias web. Este sistema foi projetado para oferecer uma experiência de usuário fluida e emocionante, garantindo a segurança e a integridade das transações e dados dos usuários.

## Funcionalidades
Nosso sistema "DinoCash" inclui uma variedade de jogos e recursos que proporcionam uma experiência única aos usuários. Abaixo estão as principais funcionalidades disponíveis:

1. **Jogos Disponíveis:**
    - **Battle**: Jogo de batalhas onde os usuários competem entre si.
    - **Bonus**: Sistema de bônus para recompensar os usuários.
    - **Coin**: Jogo de lançamento de moedas.
    - **Crash**: Jogo de multiplicador crescente onde o usuário decide quando retirar antes que o multiplicador "quebre".
    - **Dice**: Jogo de dados com diferentes modos.
    - **Double**: Jogo de aposta dupla.
    - **Fair Game**: Sistema de jogo justo garantindo transparência e confiança.
    - **Jackpot**: Jogo de jackpot com grandes prêmios.
    - **Mines**: Jogo de minas.
    - **Raffle**: Sistema de sorteio.
    - **Referência**: Sistema de referência para recompensar indicações.
    - **Revisões**: Seção para revisões de usuários.
    - **Retirada e Depósito**: Módulos para gerenciamento de depósitos e retiradas de fundos.
    - **Histórico de Jogos**: Registro detalhado do histórico de jogos dos usuários.

## Recursos Técnicos
- **Laravel Framework**: Construído com o Laravel, um dos frameworks PHP mais populares e robustos.
- **Vue.js**: Utilizado para uma experiência de front-end dinâmica e reativa.
- **Redis**: Implementado para caching eficiente e gerenciamento de sessões.
- **Socket.io**: Para comunicação em tempo real entre os clientes e o servidor.
- **Axios**: Utilizado para requisições HTTP assíncronas.
- **Bootstrap**: Framework CSS para uma interface moderna e responsiva.

## Requisitos

Para utilizar o sistema "DinoCash", os seguintes requisitos devem ser atendidos:

### Requisitos de Software
- **PHP**: Versão 7.1.3 ou superior
- **Composer**: Para gerenciar as dependências PHP
- **Node.js**: Para gerenciar as dependências JavaScript e compilar os assets
- **MySQL**: Para gerenciamento do banco de dados
- **Redis**: Para caching e gerenciamento de sessões

### Dependências PHP
- **anhskohbo/no-captcha**: Para integração com o Google reCAPTCHA
- **fideloper/proxy**: Para suporte a proxies reversos
- **laravel/framework**: Core do framework Laravel
- **laravel/tinker**: Ferramenta para interagir com o aplicativo no terminal
- **predis/predis**: Cliente Redis para PHP
- **socialiteproviders/vkontakte**: Integração com o VKontakte
- **yajra/laravel-datatables-oracle**: Plugin para manipulação de tabelas

### Dependências JavaScript
- **axios**: Para requisições HTTP assíncronas
- **bootstrap**: Framework CSS
- **popper.js**: Biblioteca para gerenciamento de pop-ups
- **cross-env**: Para definir variáveis de ambiente
- **jquery**: Biblioteca JavaScript
- **laravel-mix**: API para Webpack
- **lodash**: Biblioteca utilitária para JavaScript
- **vue**: Framework JavaScript para construção de interfaces de usuário
- **express**: Framework para Node.js
- **fs**: Biblioteca para manipulação do sistema de arquivos
- **http**: Biblioteca HTTP para Node.js
- **https**: Biblioteca HTTPS para Node.js
- **randomizer**: Biblioteca para gerar valores aleatórios
- **redis**: Cliente Redis para Node.js
- **requestify**: Cliente HTTP para Node.js
- **socket.io**: Biblioteca para comunicação em tempo real

## Manual de Instalação

**Pré-requisitos:**
- PHP 7.1.3 ou superior
- Composer
- Node.js
- MySQL
- Redis

**Passos de Instalação:**

1. **Clonar o Repositório:**
    ```bash
    git clone <url_do_repositorio>
    cd dinocash
    ```

2. **Instalar Dependências PHP:**
    ```bash
    composer install
    ```

3. **Instalar Dependências JavaScript:**
    ```bash
    npm install
    ```

4. **Configurar o Ambiente:**
    - Copie o arquivo `.env.example` para `.env`:
      ```bash
      cp .env.example .env
      ```
    - Configure as variáveis de ambiente no arquivo `.env`, especialmente as informações do banco de dados e as chaves de API.

5. **Gerar a Chave da Aplicação:**
    ```bash
    php artisan key:generate
    ```

6. **Migrar e Popular o Banco de Dados:**
    ```bash
    php artisan migrate --seed
    ```

7. **Compilar os Assets do Front-end:**
    - Para desenvolvimento:
      ```bash
      npm run dev
      ```
    - Para produção:
      ```bash
      npm run production
      ```

8. **Iniciar o Servidor:**
    ```bash
    php artisan serve
    ```

9. **Configurar o Redis:**
    - Certifique-se de que o Redis esteja instalado e configurado corretamente.
    - Atualize as configurações de cache e sessão no arquivo `.env`.

10. **Iniciar o Servidor Socket.io:**
    ```bash
    node server.js
    ```

## Demonstração

- **Conheça todo o drive de games slot:** [GameSlot Codes](https://gameslot.codes/previa-demonstracao/)

## Contribuindo

Se você deseja contribuir com o desenvolvimento deste projeto, sinta-se à vontade para abrir um pull request ou enviar issues.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

Para baixar a versão completa e as mais variadas versões, acesse [GameSlot Codes](https://www.gameslot.codes).

Aproveite o DinoCash e divirta-se! Para mais informações ou suporte, entre em contato conosco.

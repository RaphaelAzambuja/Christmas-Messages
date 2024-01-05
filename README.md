# Christmas Messages

**Christmas Messages** é uma aplicação web desenvolvida em Laravel que permite aos usuários criar e enviar mensagens personalizadas de Feliz Natal para seus entes queridos. Cada mensagem é única, e os usuários podem compartilhar o link exclusivo da mensagem com amigos e familiares.

## Como Funciona

1. **Página Inicial:**
    - Ao acessar a página inicial, os usuários são recebidos com um formulário simples que solicita seu nome (opcional) e a mensagem de Feliz Natal que desejam enviar.
2. **Link Exclusivo:**
    - Após o envio, os usuários recebem um link exclusivo para a mensagem criada.
3. **Compartilhamento:**
    - Os usuários podem compartilhar o link da mensagem com amigos e familiares por meio de redes sociais, e-mail ou qualquer método de comunicação de sua escolha.
4. **Visualização da Mensagem:**
    - Os destinatários do link são direcionados para uma página estática onde a mensagem personalizada é exibida calorosamente. Se o remetente incluiu seu nome, ele também é mostrado na mensagem.

## Requisitos do Sistema

- PHP >= 7.2.5
- Composer
- Node.js e npm
- Banco de dados relacional

## Instalação

1. **Clonar o Repositório:**

```
git clone https://github.com/RaphaelAzambuja/Christmas-Message.git
```

2. **Instalar Dependências do Composer:**

```
composer install
```

3. **Copiar o Arquivo de Configuração:**

```
cp .env.example .env
```

Configure o arquivo `.env` com as configurações do seu banco de dados e outras variáveis necessárias.

4. **Gerar a Chave da Aplicação:**

```
php artisan key:generate
```

5. **Executar as Migrações do Banco de Dados:**

```
php artisan migrate
```

6. **Iniciar o Servidor de Desenvolvimento:**

```
php artisan serve
```

Acesse a aplicação em [http://localhost:8000](http://localhost:8000/).

# UFFlix

UFFlix é um projeto que permite a transmissão de vídeos de forma simples e eficiente.

## Requisitos

- [Node.js](https://nodejs.org/) instalado em sua máquina.
- [MongoDB](https://www.mongodb.com/) em execução.

## Passos para Configuração

1. **Adicionar o Vídeo**

   - Inclua o vídeo que deseja transmitir no projeto.
   - No arquivo `index.js`, referencie o arquivo de vídeo adicionado.

2. **Iniciar o MongoDB**

   - Execute o comando:

     ```bash
     mongod
     ```

3. **Iniciar o Servidor**

   - Utilize o comando:

     ```bash
     npm start
     ```

4. **Fazer Upload do Vídeo**

   - Após iniciar o servidor, execute:

     ```bash
     curl localhost:8000/video-init
     ```

## Estrutura do Projeto

- `index.html`: Página principal do projeto.
- `index.js`: Script principal que gerencia a lógica do servidor.
- `styles.css`: Arquivo de estilos para a página.
- `docker-compose.yml`: Arquivo de configuração para o Docker Compose.
- `package.json` e `package-lock.json`: Arquivos de configuração do Node.js.
- `node_modules/`: Diretório que contém as dependências do Node.js.
- `typings/`: Diretório para definições de tipos TypeScript (se aplicável).

## Tecnologias Utilizadas

- **JavaScript**: Linguagem principal do projeto.
- **HTML**: Estrutura da página web.
- **CSS**: Estilização da página.
- **MongoDB**: Banco de dados utilizado.
- **Docker**: Para containerização do aplicativo (opcional).

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.


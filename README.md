# Vidflow

Vidflow é um projeto desenvolvido para consumir e tratar dados de uma API usando JavaScript. Utiliza programação assíncrona, uma API Fake com Node.js e JSON Server, e faz tratamento de erros com try...catch.

## Funcionalidades

- Exibir vídeos alimentados pela API
- Buscar vídeos de acordo com o título
- Filtrar vídeos por categoria

## Estrutura do Projeto

- `index.html`: Página principal do projeto
- `estilos.css`: Arquivo de estilo para a página
- `script.js`: Script principal para consumir e tratar dados da API
- `backend/`: Pasta contendo o JSON Server e o arquivo `videos.json` com os dados dos vídeos

## Requisitos

- Node.js instalado
- JSON Server

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/AntonioOliveiraa/Vidflow.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd Vidflow
    ```
3. Instale o JSON Server globalmente (caso ainda não tenha):
    ```bash
    npm install -g json-server
    ```
4. Inicie o JSON Server:
    ```bash
    json-server --watch backend/videos.json
    ```
5. Abra o arquivo `index.html` no seu navegador preferido.

## Captura de Tela

![Captura de tela da aplicação funcionando](https://github.com/user-attachments/assets/94600b4c-5343-4485-b34b-da9e15e9262b)


## Contribuindo

Atualmente, não estamos aceitando contribuições externas para este projeto.

## Licença

Este projeto possui uma licença MIT. Para mais detalhes, acesse o arquivo [LICENSE](https://github.com/AntonioOliveiraa/Vidflow/blob/main/LICENSE.md).

## Contato

[Antonio Oliveira](https://antonio-oliveira.vercel.app/)

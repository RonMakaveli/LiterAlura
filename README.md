# LiterAlura

## Descrição

O projeto **LiterAlura** é um catálogo de livros construído com Java, Spring Boot e PostgreSQL. <br>
Utilizamos a API Gutendex para buscar dados de livros e persistimos essas informações em um banco de dados relacional.

## Tecnologias Utilizadas

- Java
- Spring Boot
- PostgreSQL
- Gutendex API

## Funcionalidades

1. **Buscar livro pelo título**: Consulta a API Gutendex e insere o livro no banco de dados.
2. **Listar livros registrados**: Exibe todos os livros inseridos no banco de dados.
3. **Listar autores registrados**: Exibe todos os autores inseridos no banco de dados.
4. **Listar autores em determinado ano**: Exibe autores que estavam vivos em um ano específico.
5. **Listar livros por idioma**: Exibe livros cadastrados de acordo com o idioma.

## Configuração do Ambiente

### Pré-requisitos

- JDK (Java Development Kit) instalado.
- Maven instalado.
- PostgreSQL instalado e configurado.

## Executando o Projeto

### Passos para Executar

1. **Clone o repositório do GitHub para sua máquina local:**
   - Utilize o comando `git clone <URL_DO_REPOSITÓRIO>`.

2. **Navegue até o diretório do projeto:**
   - Utilize o comando `cd LiterAlura`.

3. **Compile o projeto utilizando Maven:**
   - Utilize o comando `mvn clean install`.

4. **Execute o projeto:**
   - Utilize o comando `mvn spring-boot:run` ou execute a classe principal diretamente na sua IDE.

5. **Acesse a aplicação:**
   - A aplicação será executada no console da sua IDE ou no terminal.

## Uso da Aplicação

Ao executar a aplicação, você verá um menu no console com as seguintes opções:
  
1. **Buscar livro pelo título**: Insira o título do livro para consultar a API e inserir no banco de dados.
2. **Listar livros registrados**: Mostra todos os livros registrados no banco de dados.
3. **Listar autores registrados**: Mostra todos os autores registrados no banco de dados.
4. **Listar autores em determinado ano**: Insira um ano para listar autores que estavam vivos nesse ano.
5. **Listar livros por idioma**: Insira o código do idioma (e.g., "PT" para português) para listar livros nesse idioma.
6. **Sair**: Encerra a aplicação.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests no repositório.

## Contato

Para dúvidas ou suporte, entre em contato via fórum ou Discord.

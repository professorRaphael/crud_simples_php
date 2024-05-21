# CRUD de Jogos
<p>Este é um projeto de exemplo para os alunos de Tecnologia Web, demonstrando como criar um CRUD (Create, Read, Update, Delete) para manipulação de dados utilizando PHP e MySQL. O projeto permite o cadastro, listagem, edição e exclusão de jogos.</p>

## Funcionalidades
- Cadastrar Jogo: Adicionar novos jogos ao banco de dados.
- Listar Jogos: Exibir uma lista de todos os jogos cadastrados.
- Editar Jogo: Atualizar as informações de um jogo existente.
- Excluir Jogo: Remover um jogo do banco de dados.

## Estrutura do Projeto
- Arquivos PHP
  - conexao.php: Configuração e conexão com o banco de dados MySQL.
  - adicionar.php: Lida com o cadastro de novos jogos.
  - atualizar.php: Lida com a atualização de jogos existentes.
  - excluir.php: Lida com a exclusão de jogos.
  - listar.php: Exibe a lista de jogos cadastrados.
  - Jogo.php: Classe que encapsula as operações CRUD para o banco de dados.
- Arquivos HTML
  - index.html: Página principal para cadastro de jogos.
- Arquivo CSS
  - style.css: Estilos básicos para a formatação das páginas HTML.

## Configuração do Banco de Dados
<p>No arquivo conexao.php, a conexão com o banco de dados é configurada e, caso o banco de dados jogos_db não exista, ele é criado juntamente com a tabela jogos.</p>

## Como Usar
- Clone este repositório para o seu servidor local.
- Certifique-se de que o servidor MySQL está em execução.
- Configure as credenciais do banco de dados no arquivo conexao.php.
- Abra o arquivo index.html em um navegador para acessar a página principal de cadastro de jogos.

# Estrutura das Tabelas
- A tabela jogos possui os seguintes campos:

  - id: Chave primária, auto-incremento.
  - nome: Nome do jogo.
  - plataforma: Plataforma do jogo.
  - genero: Gênero do jogo.


## Notas
<p><b></b>Este projeto é apenas um exemplo didático para os alunos de Tecnologia Web. Certifique-se de ajustar as configurações de acordo com o seu ambiente de desenvolvimento e tome medidas de segurança adequadas antes de utilizar em produção.</p>b></p>

# Trabalho Final de Programação para Dispositivos Moveis 2025
## Alunos
-Thales Jun Kinjo

-Gustavo Henrique Florentin Pires Pereira

-Carlos Eduardo Galvão Tomaoka
## Visão Geral do Projeto

O **UFC Fighters Manager** é um aplicativo Android desenvolvido como trabalho final da disciplina de Programação para Dispositivos Móveis (ProgMov 2025) da FACOM-UFMS. O app tem como principal objetivo registrar e visualizar informações detalhadas sobre lutadores do UFC, como suas medidas físicas, desempenho em lutas e características técnicas.

Com foco em organização, visualização rápida e segurança, o aplicativo permite que os usuários cadastrem novos personagens/lutadores, atualizem seus dados e acompanhem suas estatísticas. Utiliza banco de dados local (Room) para persistência dos dados, respeitando requisitos de usabilidade, acessibilidade e segurança.

## Usuários

O aplicativo possui um único tipo de usuário: **Usuário Registrado (Administrador dos Dados)**.

- **Usuário Registrado**
  - Pode se cadastrar no app (incluindo foto de perfil).
  - Faz login com autenticação segura (hash da senha).
  - Cadastra novos lutadores de UFC.
  - Visualiza a lista de todos os lutadores registrados.
  - Edita e remove dados de lutadores.
  - Filtra e busca lutadores pelo nome.
  - Visualiza estatísticas detalhadas de cada lutador.

## Requisitos Funcionais

- **Cadastro de Usuário**
  - Cadastro com foto de perfil.
  - Armazenamento seguro de senha (hash).
  - Validação de campos obrigatórios e formatos.
  - Prevenção de cadastro com campos vazios ou entrada inválida (ex: letras em campos numéricos).

- **Login**
  - Tela inicial com autenticação.
  - Bloqueio de acesso a usuários não cadastrados.
  - Exibição de mensagens de erro apropriadas.

- **Cadastro de Lutadores**
  - Nome do lutador.
  - Altura (em metros).
  - Peso (em kg).
  - Distância média do soco (em metros).
  - Parciais das lutas (ex: vitórias, derrotas, empates).
  - Validação completa dos dados inseridos.

- **Gerenciamento de Lutadores**
  - Listagem completa com dados principais.
  - Visualização individual com estatísticas completas.
  - Edição de dados dos lutadores.
  - Remoção segura com confirmação.

- **Filtros e Relatórios**
  - Filtro por nome.
  - Estatísticas consolidadas por lutador.

- **Tratamento de Erros e Testes de Caixa Preta**
  - Impede acesso com login inválido.
  - Alerta ao deixar campos obrigatórios vazios.
  - Validações para impedir letras em campos numéricos.
  - Prevenção de divisão por zero nas estatísticas, se aplicável.

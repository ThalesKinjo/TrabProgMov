# Trabalho Final de Programação para Dispositivos Moveis 2025
## Alunos
-Thales Jun Kinjo

-Gustavo Henrique Florentin Pires Pereira

-Carlos Eduardo Galvão Tomaoka

## Visão Geral do Projeto

O **FifaGame** é um aplicativo Android desenvolvido como projeto final da disciplina de Programação para Dispositivos Móveis (ProgMov 2025) da FACOM-UFMS. Seu objetivo é facilitar o gerenciamento de partidas de FIFA Soccer entre jogadores, permitindo o registro de resultados, estatísticas e histórico de confrontos.

O sistema permite o cadastro de usuários com autenticação segura, armazenamento de foto de perfil e gerenciamento completo de jogos disputados. O projeto utiliza o banco de dados local Room, respeita princípios de usabilidade, acessibilidade e segurança, e foi desenvolvido utilizando os principais componentes modernos do Android Studio.

## Usuários

O aplicativo possui um único perfil de usuário: **Jogador Registrado**.

- **Jogador Registrado**
  - Realiza login e cadastro no sistema (com foto e senha segura).
  - Registra partidas disputadas contra outros jogadores.
  - Visualiza histórico de partidas e estatísticas pessoais.
  - Edita ou remove partidas registradas.
  - Filtra jogos pelo nickname de outros jogadores.
  - Acessa sua foto de perfil e dados pessoais com segurança.

## Requisitos Funcionais

- **Cadastro de Usuários**
  - Cadastro com foto de perfil e senha (armazenada com hash).
  - Validação de campos obrigatórios e formatos de dados.
  - Tratamento de erros como campos vazios ou entrada inválida (ex: texto em campo numérico).

- **Login de Usuários**
  - Tela inicial de autenticação.
  - Impede acesso de usuários não cadastrados.

- **Gerenciamento de Partidas**
  - Inserção de dados de uma nova partida: jogadores, placar, data.
  - Edição e exclusão de partidas registradas.
  - Visualização de partidas anteriores em uma lista.

- **Relatórios e Filtros**
  - Filtro de partidas por nickname do adversário.
  - Relatório simples de desempenho individual.

- **Tratamento de Erros e Validações**
  - Erros de login (usuário inexistente ou senha incorreta).
  - Campos obrigatórios validados.
  - Prevenção de divisão por zero ou entrada de dados incompatíveis.

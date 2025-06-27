# Casos de Uso


## Caso de Uso 1: Cadastrar Reserva
- **Ator principal:** Funcionário do UniSenac
- **Resumo:** Permite o cadastro de uma nova reserva de sala para um evento, curso ou disciplina.
- **Fluxo principal:**
  1. O usuário acessa a página de cadastro de reservas.
  2. Informa os dados da reserva nos filtros de pesquisa: data, turno, unidade, tipo de reserva.
  3. O sistema mostra uma tabela com as salas disponíveis.
  4. O usuário ajusta as datas se necessário e escolhe a sala clicando no botão “reservar”.
  5. O usuário escolhe uma turma já existente ou preenche os dados de uma nova turma, preenche o campo de responsável pelo cadastro e confirma.
  6. O sistema valida os dados e registra a reserva.
  7. Exibe mensagem de sucesso.


## Caso de Uso 2: Consultar Reservas
- **Ator principal:** Funcionário do UniSenac
- **Resumo:** Permite visualizar todas as reservas cadastradas, com filtros por data, turno e unidade.
- **Fluxo principal:**
  1. O usuário acessa a página de consulta de reservas.
  2. Aplica filtros conforme necessidade.
  3. Visualiza as reservas em uma tabela interativa.
  4. Pode clicar em uma reserva para editar ou excluir.


## Caso de Uso 3: Gerenciar Salas
- **Ator principal:** Funcionário do Unisenac
- **Resumo:** Permite cadastrar, editar e excluir salas disponíveis para reserva.
- **Fluxo principal:**
  1. O administrador acessa a página de gerenciamento de salas.
  2. Cadastra uma nova sala, edita ou exclui uma existente.
  3. Informa atributos como tipo, número, capacidade, equipamentos, unidade, observações.
  4. O sistema salva as informações no banco de dados.


## Caso de Uso 4: Cadastrar e Editar Turmas
- **Ator principal:** Funcionário do UniSenac
- **Resumo:** Permite cadastrar novas turmas ou editar informações de turmas existentes.
- **Fluxo principal:**
  1. O usuário acessa o formulário de cadastro/edição de turma.
  2. Preenche os dados da turma: nome, curso, docente, número de alunos.
  3. O sistema valida e armazena os dados.

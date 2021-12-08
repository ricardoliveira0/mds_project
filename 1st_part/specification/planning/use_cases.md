## Signup
* **Main Actor:** Docente da UC, Responsável da empresa, Aluno, Tutor, Orientador.  
* **Main Success Scenario:** 
  1. Clicar no botão ***signup***;
  2. Preencher os *fields* obrigatórios;
  3. Clicar no botão de ***submissão***.
\
&nbsp;
## Login
* **Main Actor:** Docente da UC, Responsável da empresa, Aluno, Tutor, Orientador.  
* **Main Success Scenario:** 
  1. Preencher as credenciais de acesso;
  2. Clicar no botão ***login***;
  3. Acesso à plataforma garantido.
* **Extensions:** 
  * 2a. Falha no *login*.
    * *Username* não encontrado;
    * *Password* incorreta.
\
&nbsp;
## Submissão de propostas de estágio
* **Main Actor:** Responsável da empresa
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***propostas***;
  3. Clicar no botão ***realizar submissão***;
  4. Introduzir nos *fields* todas as informações referentes à proposta;
  5. Realizar a submissão, clicando no botão ***submeter***.
* **Extensions:**
  * 3a. O sistema não garante privilégio.
    * O utilizador não tem os privilégios necessários para realizar a operação.
\
&nbsp;
## Aprovação de propostas de estágio
* **Main Actor:** Docente da UC
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***propostas***;
  3. Clicar no botão ***aprovações***;
  4. Listar todas as propostas;
  5. Clicar no botão ***concluir***.
* **Extensions:**
  * 3a. O sistema não garante privilégio.
    * O utilizador não tem os privilégios necessários para realizar a operação.
  * 4a. Selecionar a *checkbox* nas propostas a aprovar.
  * 4b. Desselecionar a *checkbox* nas propostas previamente aprovadas.
\
&nbsp;
## Realizar candidatura
* **Main Actor:** Aluno
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***propostas***;
  3. Listar todas as propostas;
  4. Selecionar as *checkboxes* das propostas de maior interesse;
  5. Clicar no botão ***seguinte***;
  6. Ordenar as propostas de maior interesse para menor;
  7. Clicar no botão ***concluir***.
* **Extensions:**
  * 5a. O sistema não garante privilégio.
    * O utilizador não é 'Aluno', portanto não tem os privilégios necessários para realizar a operação.
  * 5b. O utilizador não selecionou nenhuma proposta.
    * 1. Até ao utilizador não selecionar pelo menos uma proposta, não poderá avançar;
    * 2. Retorna ao passo **4.**.
  * 5c. O utilizador não selecionou três propostas.
    * 1. O sistema mostra um alerta de que o utilizador pode ainda selecionar mais *x* propostas;
    * 2. O utilizador pode prosseguir ou editar a sua escolha.
\
&nbsp;
## Seriação de candidatos às propostas de estágio
* **Main Actor:** Responsável da empresa
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***propostas***;
  3. Clicar no botão ***seriação***;
  4. Listar todos os estágios da empresa associada ao utilizador;
  5. Clicar numa proposta de estágio;
  6. Listar todos os alunos (e respetivos detalhes) que realizaram candidatura ao estágio;
  7. Clicar nas *checkboxes* dos alunos que pretende seriar;
  8. Clicar no botão ***seguinte***;
  9. Ordenar os alunos, previamente selecionados, por ordem de maior interesse para menor;
  10. Clicar no botão ***concluir***.
* **Extensions:**
  * 3a. O sistema não garante privilégio.
    * O utilizador não tem os privilégios necessários para realizar a operação.
  * 4a. Nenhum estágio listado.
    * Nenhuma proposta de estágio foi submetida;
    * Nenhuma proposta de estágio foi aprovada pelos Docentes da UC.
  * 4b. Estágio listado com clique desativado.
    * Nenhum aluno se candidatou ao estágio, logo é listado com estilo *disabled*.
  * 8a. O utilizador não selecionou nenhum Aluno.
    * 1. O sistema mostra um alerta de que nenhum aluno foi selecionado;
    * 2. O utilizador pode prosseguir ou editar a sua escolha.
  * 8b. O utilizador não selecionou todos os alunos.
    * 1. O sistema mostra um alerta de que nem todos os alunos foram selecionados;
    * 2. O utilizador pode prosseguir ou editar a sua escolha.
\
&nbsp;
## Atribuir estágio a Aluno
* **Main Actor:** Docente da UC
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***propostas***;
  3. Clicar no botão ***atribuição***;
  4. Listar todas as propostas de estágios;
  5. Clicar numa proposta de estágio;
  6. Listar todos os alunos que se candidataram ao estágio selecionado, exibindo tanto o grau de preferência do Aluno como a seriação realizada pelo Responsável da empresa;
  7. Clicar nas *checkboxes* dos alunos que pretende atribuir definitivamente ao estágio selecionado;
  8. Clicar no botão ***seguinte***;
  9. Listar todos os docentes do departamento;
  10. Clicar na *checkbox* do docente que pretende atribuir como Tutor ao estágio selecionado.
  11. Clicar no botão **concluir***.
* **Extensions:**
  * 3a. O sistema não garante privilégio.
    * O utilizador não tem os privilégios necessários para realizar a operação.
  * 4a. Nenhum estágio listado.
    * Nenhuma proposta de estágio foi submetida;
    * Nenhuma proposta de estágio foi aprovada pelos Docentes da UC.
  * 4b. Estágio listado com clique desativado.
    * Nenhum aluno se candidatou ao estágio, logo é listado com estilo *disabled*.
  * 8a. O utilizador não selecionou nenhum Aluno.
    * 1. O sistema mostra um alerta de que nenhum aluno foi selecionado;
    * 2. O utilizador não poderá prosseguir até eleger pelo menos um Aluno.
  * 8b. O utilizador não selecionou todos os alunos.
    * 1. O sistema mostra um alerta de que nem todos os alunos foram selecionados, isto é, o estágio ainda tem vaga para mais alunos;
    * 2. O utilizador pode prosseguir ou editar a sua escolha.
  * 9a. Nenhum docente listado.
    * Nenhum docente do departamento disponível para Tutor na UC de Estágio.
  * 9b. Docente listado com clique desativado.
    * O Docente já acompanha o limite máximo de estágios como Tutor, logo é listado como *disabled*.
\
&nbsp;
## Avaliar Aluno
* **Main Actor:** Docente da UC, Orientador, Tutor
* **Main Success Scenario:** 
  1. Efetuar *login*;
  2. Clicar no botão ***estágios***;
  3. Clicar no botão ***avaliar***;
  4. Listar todos os estágios que acompanha;
  5. Clicar num estágio;
  6. Listar todos os alunos que se encontram no estágio selecionado;
  7. Clicar num Aluno;
  8. Introduzir nos *fields* todas as informações relativamente à avaliação;
  9. Clicar no botão ***concluir***;
* **Extensions:**
  * 3a. O sistema não garante privilégio.
    * O utilizador não tem os privilégios necessários para realizar a operação.
  * 4a. Nenhum estágio listado.
    * O utilizador não se encontra associado a nenhum estágio;
    * O utilizador já avaliou todos os alunos de todos os estágios que lhe foram atribuídos.
  * 4b. Estágio listado com clique desativado.
    * O estágio ainda não foi concluído, portanto, não é possível realizar avaliação.
  * 6a. Nenhum aluno listado.
    * O estágio pode ter sido cancelado;
    * O Aluno pode ter desistido do estágio.

  
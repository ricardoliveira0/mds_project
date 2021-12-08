## Requisitos de Utilizador
* O sistema deve permitir o **registo** de cada utilizador, sendo-lhes atribuídas diferentes funcionalidades, consoante a sua posição:
  * Docente da UC 'Estágio';
  * Responsável da empresa;
  * Aluno;
  * Docente tutor;
  * Orientador da empresa.
* Permitir a submissão de propostas de estágio, ficando cada uma delas pendente de aprovação.
* Conceder **consulta** às propostas aprovadas e possibilidade de realizar **submissão de candidatura** às mesmas.
* Atribuir o estágio e respetivo tutor.
* Permitir a atribuição da avaliação final.
\
&nbsp;
## Requisitos de Sistema
* Sistema de **login** para todos os utilizadores.
* O sistema deve reconhecer os diferentes *roles* atribuídos a cada utilizador, de modo a disponibilizar corretamente a informação e/ou funcionalidades a cada um deles.
* As propostas de estágio a serem submetidas, devem conter _fields_ para toda a informação da mesma:
  * Descrição do estágio;
  * Objetivos do estágio;
  * Ferramentas/tecnologias utilizadas;
  * Indicação se o estágio é remoto ou presencial;
  * Indicação se o estágio é remunerado ou não;
  * Número de vagas para o estágio;
  * Orientador do estágio na empresa.
* O sistema deve **importar todas as informações** relativas aos **alunos** inscritos na UC 'Estágio', bem como os **Docentes** do Departamento de Informática que se disponibilizam para **Tutores** de estágios.
* Os utilizadores com privilégios de **Docente da UC 'Estágio'**, são os únicos que podem rever as submissões de propostas de estágio de modo a **aprová-las ou rejeitá-las**.
* Após a análise de todas as propostas, estas devem ser disponibilizadas para qualquer Aluno.
* A qualquer momento do semestre, somente os utilizadores com privilégios de **Docente da UC 'Estágio'**, poderão realizar alguma alteração às atribuições previamente ocorridas.
* Uma vez que um Aluno é atribuído a um estágio, deve ser retirado da listagem de alunos que é mostrada aquando da atribuição destes a um estágio. Evitando assim que um Aluno seja atribuído, por erro, a mais do que um estágio.
* No final do semestre, a **nota final** deve ser calculada e cedida a cada Aluno, somente quando as **três componentes** estiverem avaliadas pelos responsáveis de cada uma.
* O **sistema necessita de uma** conexão a uma **base de dados**, de modo a conseguir gerir corretamente toda a informação e, possibilitar, consultar registos de anos anteriores.

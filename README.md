# Projeto de Agenda Virtual

### Tecnologias Utilizadas:
<ul>
  <li>JavaScript: Usado para manipulação da interface do usuário e interações dinâmicas.</li>
  <li>Node.js: Usado para estabelecer a conexão entre a aplicação e o banco de dados PostgreSQL.</li>
  <li>HTML/CSS: Usados para criar e estilizar a interface do usuário.</li>
  <li>SQL: Usado para gerenciar as tabelas e registros no banco de dados.</li>
  <li>PostgreSQL: Sistema de gerenciamento de banco de dados relacional utilizado no projeto.</li>
</ul>

### Descrição do Projeto
Este projeto é uma agenda virtual que permite o agendamento, por parte dos clientes, de compromissos, especificando nome, data, horário, profissional e procedimento. As informações são armazenadas em um banco de dados utilizando PostgreSQL e exibidas em uma tabela na interface do usuário.

### Funcionalidades
<ul>
  <li>Agendamento de Compromissos: O usuário pode inserir o nome do cliente, a data, o horário, o profissional e o procedimento desejado, e agendar o compromisso. Os dados são enviados para o banco de dados através de uma conexão com Node.js.</li>
  <li>Exclusão de Agendamentos: O usuário pode excluir compromissos da tabela de agendamentos. Os agendamentos excluídos são removidos da tabela principal e registrados em uma tabela de backup.</li>
  <li>Visualização de Agendamentos Excluídos: A aplicação exibe uma tabela separada na interface do usuário que lista todos os agendamentos que foram excluídos, armazenados na tabela de backup.</li>
</ul>

### Integrantes
<ul>
  <li><a href="https://github.com/anabmferraz">Ana Beatriz Maciel Ferraz</a></li>
  <li><a href="https://github.com/brendacristaldo">Brenda Beatriz Cristaldo</a></li>
  <li><a href="https://github.com/Thakirian">Thaisse Kirian Veiga</a></li>
  <li><a href="https://github.com/nathaliamiyuki">Nathalia Miyuki</a></li>
</ul>

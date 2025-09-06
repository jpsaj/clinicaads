# Requisitos Funcionais para Agenda Médica

## R1 - Cadastro de Médicos  
**RF1** - O sistema deve possibilitar o cadastro de médicos com os seguintes dados: nome completo, CRM, especialidade, disponibilidade, CPF e contato.

## R2 - Cadastro de Pacientes  
**RF2** - O sistema deve possibilitar o cadastro de pacientes com os seguintes dados: nome completo, endereço, CPF, sexo, data de nascimento e contato.

## R3 - Cadastro de Recepcionistas  
**RF3** - O sistema deve possibilitar o cadastro de perfis de recepcionistas, que devem ter permissão para cadastrar médicos e pacientes.

## R4 - Agendamento de Consultas  
**RF4** - O sistema deve possibilitar a visualização da disponibilidade dos médicos e permitir o agendamento de consultas nos horários disponíveis.

## R5 - Alterações em Consultas  
**RF5** - O sistema deve possibilitar cancelamento, reagendamento e inclusão de consultas, de acordo com a autorização por perfil do usuário.

## R6 - Gerenciamento de Agenda do Médico  
**RF6** - O médico deve possuir acesso à sua agenda, podendo ajustar seus horários conforme disponibilidade.

## R7 - Notificações e Lembretes  
**RF7** - O sistema deve notificar o médico com lembretes de sua agenda, sendo possível configurar os lembretes no sistema.

## R8 - Confirmação de Presença  
**RF8** - O sistema deve solicitar confirmação de presença do paciente, enviando lembretes para que o atendimento confirme por ligação ou outro meio que a clínica considerar viável.

## R9 - Filtragem e Busca  
**RF9** - O sistema deve permitir consulta de pacientes e médicos por CPF e nome. Ao consultar, deve permitir editar cadastro ou agendar nova consulta.

## R10 - Relatórios  
**RF10** - O sistema deve possuir módulo de relatórios gerenciais, disponibilizando informações das agendas médicas por especialidade, dia, mês, ano e horários.

---

# Requisitos Não Funcionais

**RNF1 – Segurança dos Dados**  
O sistema deve garantir a proteção das informações pessoais e médicas dos pacientes, utilizando criptografia para armazenamento e transmissão dos dados, além de implementar controle de acesso baseado em autenticação e autorização dos usuários.

**RNF2 – Disponibilidade**  
O sistema deve estar disponível para uso pelos usuários com um tempo mínimo de 99,5%, permitindo o acesso à agenda a qualquer momento.

**RNF3 – Usabilidade**  
A interface do sistema deve ser intuitiva e fácil de usar para médicos, recepcionistas e pacientes, incluindo suporte a dispositivos móveis, com menus claros e feedback imediato para as ações do usuário.

**RNF4 – Desempenho**  
O sistema deve responder às solicitações dos usuários (como buscas e agendamentos) em até 2 segundos, mesmo sob alta carga e com grande volume de dados armazenados.

**RNF5 – Backup e Recuperação**  
O sistema deve realizar backups automáticos diários dos dados e permitir a recuperação rápida das informações em caso de falhas ou perda de dados.

---

# Requisitos de Software para Sistema SaaS de Agenda Médica

**RS1 – Multiusuário e Multitenancy**  
O sistema deve suportar múltiplos usuários e múltiplas clínicas/consultórios (tenants) isolados, garantindo que os dados de cada cliente sejam acessíveis somente por seus usuários autorizados.

**RS2 – Acesso via Navegador Web**  
O sistema deve ser acessível via navegadores modernos (Chrome, Firefox, Edge, Safari) sem necessidade de instalação de software adicional no dispositivo do usuário.

**RS3 – Escalabilidade**  
O software deve ser capaz de escalar automaticamente para suportar aumento no número de usuários e volume de dados, garantindo desempenho estável mesmo com crescimento da base.

**RS4 – Atualizações Automáticas**  
O sistema deve permitir a implantação de atualizações e correções de forma automática e transparente para os usuários, sem necessidade de interrupção dos serviços.

**RS5 – Monitoramento e Logging**  
O sistema deve possuir mecanismos de monitoramento contínuo e registro de logs para análise de performance, detecção de falhas e auditoria de segurança.

#Requisitos funcionais para 
R1 - Quero cadastro os médicos
RF1 - Sistema deve possibilitar o cadsatro de médicos com os seguintes dados: nome completo, crm, especilidade, disponibilidade, cpf e contato. 

R2 - Quero cadastrar os pacientes
RF2 - Sistema deve possibilitar o cadsatro de pacientes com os seguintes dados: nome completo, endereço, cpf, sexo, data de nascimento e contato.
R3 - Quero cadastrar recepcionistas
RF3: Deve possibilitar o cadastro de perfis de recepcionalistas, que deve permitir cadastrar médicos e pacientes. 
R4 - Quero agendar consultas para os médicos
RF4: Deve possibilitar visualização de disponibilidade dos médicos e possibilitar o agendamento de consultas nos horários disponíveis.
R5 - Preciso realizar alterações quando necessário, seja cancelamento ou reagendamento de consulta. 
RF5: Sistema deve possibilitar cancelamento, reagendamento e inclusão de consulta, de acordo com autorização por perfil. 
R6 - Gerenciamento de Agenda do Médico
RF6 - Médico deve possuir acesso a sua agenda, podendo ajustar sua agenda conforme disponibilidade. 
R7 - Notificações e Lembretes
RF7 - Sistema deve notificar o médico com lembretes de sua agenda, lembretes podem ser configurados em sistema.
R8 - Confirmação de Presença
RF8 - Sistema deve solicitar confirmação de presença do paciente, lembrete será enviado para o atendimento que deverá realizar a confirmação por ligação ou outro meio que clinica entender como viável. 
R9 - Filtragem e Busca
RF9 - Sitema deve permitir consulta de pacientes e médicos por CPF e Nome, quando consultado deve permitir editar cadastro ou agendar nova consulta. 
R10 - Relatórios
RF10- Sistema deve possui módulo de relatórios gerenciais, disponibilizando informações das agendas médicas por especilidade, dia, mês, ano  e horários. 


Requisitos não funcionais

RNF1 – Segurança dos Dados
O sistema deve garantir a proteção das informações pessoais e médicas dos pacientes, utilizando criptografia para armazenamento e transmissão dos dados, além de implementar controle de acesso baseado em autenticação e autorização dos usuários.
RNF2 – Disponibilidade
O sistema deve estar disponível para uso pelos usuários com um tempo mínimo de 99,5%, permitindo o acesso à agenda a qualquer momento.
RNF3 – Usabilidade
A interface do sistema deve ser intuitiva e fácil de usar para médicos, recepcionistas e pacientes, incluindo suporte a dispositivos móveis, com menus claros e feedback imediato para as ações do usuário.
RNF4 – Desempenho
O sistema deve responder às solicitações dos usuários (como buscas e agendamentos) em até 2 segundos, mesmo sob alta carga e com grande volume de dados armazenados.
RNF5 – Backup e Recuperação
O sistema deve realizar backups automáticos diários dos dados e permitir a recuperação rápida das informações em caso de falhas ou perda de dados.

Requisitos de Software para Sistema SaaS de Agenda Médica

RS1 – Multiusuário e Multitenancy
O sistema deve suportar múltiplos usuários e múltiplas clínicas/consultórios (tenants) isolados, garantindo que os dados de cada cliente sejam acessíveis somente por seus usuários autorizados.
RS2 – Acesso via Navegador Web
O sistema deve ser acessível via navegadores modernos (Chrome, Firefox, Edge, Safari) sem necessidade de instalação de software adicional no dispositivo do usuário.
RS3 – Escalabilidade
O software deve ser capaz de escalar automaticamente para suportar aumento no número de usuários e volume de dados, garantindo desempenho estável mesmo com crescimento da base.
RS4 – Atualizações Automáticas
O sistema deve permitir a implantação de atualizações e correções de forma automática e transparente para os usuários, sem necessidade de interrupção dos serviços.
RS5 – Monitoramento e Logging
O sistema deve possuir mecanismos de monitoramento contínuo e registro de logs para análise de performance, detecção de falhas e auditoria de segurança.
RS6 - 

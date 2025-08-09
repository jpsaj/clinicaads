# Documento de Visão – Sistema de Agendamento de Consultas

## Objetivo

O objetivo deste projeto é otimizar e automatizar o agendamento de consultas e retornos, proporcionando maior controle e organização à gestão da agenda dos profissionais que prestam serviço para a clínica. O sistema permitirá que os profissionais registrem a evolução dos pacientes e finalizem os atendimentos de forma centralizada.

---

## Escopo

### Escopo IN (Incluído)
- Cadastro de usuários;
- Cadastro de pacientes;
- Cadastro e gerenciamento da disponibilidade dos médicos;
- Definição de janelas de atendimento;
- Agendamento e cancelamento de consultas;
- Visualização da agenda diária e semanal;
- Exibição de mensagens de erro em caso de conflitos de horário.

### Escopo OUT (Fora do Escopo)
- Agendamento realizado pelo paciente fora da clínica (ex: em casa);
- Envio de mensagens ou notificações para pacientes;
- Funcionalidades de faturamento;
- Prontuário eletrônico;
- Relatórios e dashboards avançados;
- Suporte para múltiplas clínicas ou unidades (multi-clínica/multi-unidade).

---

## Regras de Negócio (RB)

- **RB-001**: Um slot de horário não pode se sobrepor a outro já ocupado.
- **RB-002**: Consultas devem ocorrer apenas dentro da janela de atendimento definida para cada profissional.
- **RB-003**: O cancelamento de uma consulta deve liberar imediatamente o slot correspondente.
- **RB-004**: A duração padrão de uma consulta é de 30 minutos, podendo ser configurada individualmente por profissional.

---

## Premissas

- O horário comercial base é das **08h às 18h**, podendo ser ajustado conforme o profissional;
- O MVP será limitado a **uma única clínica** com **até 10 profissionais**;
- Um banco de dados inicial estará disponível para suportar o sistema.

---

## Stakeholders (Partes Interessadas)

- Atendentes;
- Médicos;
- Pacientes;
- Gestor da clínica.

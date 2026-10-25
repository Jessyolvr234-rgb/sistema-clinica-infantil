# Sistema de Gestão de Atendimentos Terapêuticos Infantis

Sistema web desenvolvido para centralizar e otimizar a gestão administrativa, operacional e terapêutica de uma clínica especializada em atendimentos infantis, com possibilidade de utilização em duas unidades.

O projeto busca substituir controles manuais e informações dispersas por uma plataforma organizada, segura e intuitiva, facilitando o gerenciamento de pacientes, responsáveis, profissionais, agendas, atendimentos, relatórios e informações financeiras.

**Status:** Em planejamento e desenvolvimento.

---

**Sobre o projeto**

O Sistema de Gestão de Atendimentos Terapêuticos Infantis surgiu da necessidade de melhorar a organização das atividades de uma clínica que oferece atendimentos especializados para crianças.

Entre os principais desafios identificados estão o gerenciamento de agendamentos recorrentes, o controle de presença e faltas, a consulta de disponibilidade dos profissionais, a preservação do histórico de atendimentos e o cálculo da produção mensal dos terapeutas.

A plataforma será desenvolvida para centralizar essas operações, respeitando as responsabilidades e permissões de cada usuário, com possibilidade de expansão conforme as necessidades da clínica.

## Objetivos

- Centralizar os cadastros de pacientes, responsáveis, profissionais e unidades.
- Organizar agendas individuais e recorrentes.
- Registrar presenças, faltas, cancelamentos e remarcações.
- Preservar o histórico de atendimentos e alterações realizadas.
- Disponibilizar uma área exclusiva para os profissionais.
- Facilitar o registro e a consulta de relatórios dos pacientes.
- Gerenciar comunicados e orientações internas.
- Controlar pagamentos e calcular a produção mensal dos profissionais.
- Gerar relatórios administrativos e financeiros básicos.
- Garantir segurança, privacidade e controle de acesso às informações.

## Funcionalidades previstas

### 1. Autenticação e controle de acesso

- Login com usuário e senha.
- Permissões específicas conforme o perfil de acesso.
- Gerenciamento de usuários autorizados.
- Restrição de acesso a informações administrativas, financeiras e clínicas.
- Registro de alterações importantes realizadas no sistema.

### 2. Gestão de pacientes e responsáveis

- Cadastro e atualização de pacientes.
- Cadastro de responsáveis e vinculação aos pacientes.
- Possibilidade de associar mais de um responsável a um paciente.
- Possibilidade de vincular um responsável a mais de um paciente.
- Identificação da unidade de referência.
- Controle da situação do acompanhamento: ativo ou inativo.
- Acesso restrito às informações clínicas necessárias ao atendimento.

### 3. Gestão de profissionais

- Cadastro de profissionais e informações de contato.
- Registro de profissão e especialidade.
- Registro profissional, quando aplicável.
- Associação dos profissionais às unidades de atuação.
- Gerenciamento de disponibilidade de horários.
- Controle da situação cadastral e do acesso ao sistema.

### 4. Gestão de unidades

- Cadastro de unidades da clínica.
- Registro de endereço, telefone e horário de funcionamento.
- Vinculação de profissionais às respectivas unidades.
- Organização das agendas e dos atendimentos por unidade.
- Controle de acesso às informações de cada unidade conforme as permissões definidas.

### 5. Agenda e atendimentos recorrentes

- Criação de atendimentos individuais e recorrentes.
- Associação de paciente, profissional, serviço, unidade, data e horário.
- Consulta de disponibilidade dos profissionais.
- Identificação de conflitos de horários.
- Remarcação e cancelamento de sessões.
- Registro de presença e falta.
- Alteração de uma sessão específica ou das sessões futuras de uma recorrência.
- Preservação dos atendimentos anteriores e de seu histórico.

**Regra fundamental:** alterações em agendamentos recorrentes não deverão modificar indevidamente sessões passadas nem comprometer a consistência dos horários futuros.

### 6. Área do Profissional

Cada profissional contará com uma área exclusiva para acompanhar suas atividades.

**Minha agenda**
- Visualização dos atendimentos do dia, da semana e do mês.
- Consulta de horários, pacientes, unidades e tipos de atendimento.
- Identificação de sessões confirmadas, realizadas, canceladas e faltas.
- Consulta das alterações realizadas na agenda.

**Meus pacientes**
- Lista de pacientes vinculados ao profissional.
- Consulta da quantidade de pacientes ativos.
- Acesso ao histórico dos atendimentos autorizados.
- Consulta das informações necessárias à realização das sessões.

**Relatórios dos pacientes**
- Criação de relatórios individuais.
- Registro da data e do tipo de atendimento.
- Descrição das atividades realizadas e observações pertinentes.
- Registro da evolução observada durante a sessão.
- Salvamento de rascunhos.
- Finalização de relatórios e vinculação ao histórico do paciente.
- Consulta de relatórios anteriores autorizados.

**Comunicados**
- Consulta de avisos publicados pela administração.
- Acesso a orientações internas, reuniões, feriados e mudanças de funcionamento.
- Consulta de comunicados recentes e anteriores disponíveis.

**Resumo profissional**
- Total de pacientes ativos vinculados.
- Atendimentos agendados para o dia.
- Atendimentos realizados no mês.
- Faltas e cancelamentos registrados.
- Relatórios pendentes de finalização.
- Consulta da própria produção mensal, quando autorizada.

### 7. Controle financeiro

- Registro de pagamentos.
- Consulta de valores recebidos e pendentes.
- Registro de formas e datas de pagamento.
- Associação de sessões às respectivas cobranças.
- Geração de relatórios financeiros básicos.
- Cálculo da produção mensal dos profissionais conforme as regras definidas pela clínica.

Os critérios de cálculo deverão ser configuráveis e transparentes, permitindo a conferência dos valores e a preservação do histórico de regras financeiras.

### 8. Comunicados internos

- Publicação de comunicados pela administração.
- Definição de título, mensagem, autor e data de publicação.
- Seleção dos destinatários ou grupos de profissionais.
- Definição de validade, quando necessária.
- Consulta de comunicados recentes e anteriores.
- Possibilidade de indicar avisos ainda não visualizados.

### 9. Dashboard administrativo

O painel administrativo reunirá indicadores para facilitar o acompanhamento das operações da clínica, incluindo:

- Total de pacientes ativos.
- Quantidade de profissionais cadastrados.
- Atendimentos do dia.
- Presenças, faltas e cancelamentos.
- Indicadores financeiros básicos.
- Produção mensal dos profissionais.
- Informações agrupadas por unidade, conforme as permissões do usuário.

### 10. Relatórios administrativos

O sistema deverá disponibilizar consultas e relatórios com filtros por período, unidade e profissional, respeitando as permissões de acesso.

Relatórios previstos:

- Pacientes ativos.
- Agendamentos por período.
- Frequência dos pacientes.
- Atendimentos realizados.
- Faltas e cancelamentos.
- Produção mensal dos profissionais.
- Pagamentos recebidos e pendentes.

A exportação para PDF ou planilhas poderá ser incluída conforme a prioridade e as necessidades da clínica.

### 11. Configurações

Uma área centralizada permitirá que usuários autorizados gerenciem os parâmetros gerais do sistema.

Estão previstas configurações para:

- Dados institucionais e informações das unidades.
- Dias e horários de funcionamento.
- Duração padrão dos atendimentos e intervalos.
- Regras de remarcação, cancelamento e recorrência.
- Especialidades e serviços oferecidos.
- Valores de referência dos serviços.
- Usuários, perfis e permissões.
- Critérios financeiros e cálculo da produção.
- Comunicados e notificações.
- Registros de alterações importantes.
- Procedimentos de backup e recuperação, conforme a infraestrutura.

---

## Perfis de acesso

O sistema contará inicialmente com três perfis principais:

| Perfil | Responsabilidades |
|---|---|
| **Administrador** | Gestão geral, cadastros, unidades, agendas, configurações, permissões e relatórios administrativos e financeiros. |
| **Recepcionista** | Cadastro de pacientes e responsáveis, agendamentos, consulta de disponibilidade, registro de presença e operações autorizadas. |
| **Profissional** | Consulta da própria agenda, acesso aos pacientes vinculados, elaboração de relatórios e consulta de comunicados internos. |

Cada perfil terá acesso somente às funcionalidades e informações necessárias para suas atividades.

## Escopo do MVP

O MVP (*Minimum Viable Product*, ou Produto Mínimo Viável) será a primeira versão funcional do sistema, priorizando os recursos essenciais para utilização e validação pela clínica.

O escopo inicial contempla:

- [ ] Login e controle de acesso por perfil.
- [ ] Cadastro de pacientes e responsáveis.
- [ ] Cadastro de profissionais e especialidades.
- [ ] Cadastro e consulta das unidades.
- [ ] Agenda individual e atendimentos recorrentes.
- [ ] Registro de presenças, faltas e cancelamentos.
- [ ] Área do profissional com agenda e lista de pacientes.
- [ ] Criação e consulta de relatórios por paciente.
- [ ] Comunicados publicados pela administração.
- [ ] Configurações básicas centralizadas.
- [ ] Controle financeiro básico e cálculo da produção mensal.
- [ ] Dashboard e relatórios administrativos essenciais.

*Os itens acima representam o escopo planejado; as marcações deverão ser atualizadas conforme as funcionalidades forem implementadas e testadas.*

## Funcionalidades para versões futuras

Após a validação da primeira versão, poderão ser avaliadas novas funcionalidades, como:

- Integração automática com WhatsApp.
- Aplicativo para dispositivos móveis.
- Portal de acesso para responsáveis.
- Assinatura eletrônica avançada de documentos.
- Integração com sistemas externos.
- Recursos clínicos avançados.
- Indicadores estatísticos complexos.
- Automação de cobranças e pagamentos.
- Exportação ampliada de relatórios.

A inclusão dessas funcionalidades dependerá das prioridades da clínica e do planejamento técnico do projeto.

## Requisitos não funcionais

Além das funcionalidades, o sistema deverá considerar os seguintes requisitos:

- **Usabilidade:** interface simples, intuitiva e responsiva.
- **Compatibilidade:** funcionamento em navegadores modernos.
- **Segurança:** proteção dos dados pessoais e clínicos.
- **Controle de acesso:** permissões adequadas a cada perfil.
- **Integridade:** prevenção de conflitos e inconsistências nos agendamentos.
- **Rastreabilidade:** preservação do histórico de atendimentos e alterações importantes.
- **Recuperação:** procedimentos de backup e recuperação dos dados.
- **Desempenho:** resposta adequada ao volume de utilização da clínica.
- **Manutenibilidade:** estrutura organizada que facilite correções e evolução do sistema.

## Segurança e privacidade

Como o sistema envolve dados pessoais de crianças, responsáveis e informações relacionadas à saúde, a segurança será uma prioridade durante o desenvolvimento.

Serão consideradas as seguintes medidas:

- Controle de acesso baseado em perfis e vínculos autorizados.
- Proteção das informações clínicas contra consultas indevidas.
- Armazenamento seguro de senhas utilizando técnicas adequadas de hash.
- Preservação dos registros e histórico de alterações.
- Proteção de credenciais, chaves e variáveis de ambiente.
- Planejamento de backups e recuperação de dados.
- Observância da Lei Geral de Proteção de Dados Pessoais (LGPD) e das normas aplicáveis.

**Importante:** dados reais de pacientes, documentos pessoais, senhas, chaves de API e outras informações confidenciais não devem ser publicados no repositório. Os testes deverão utilizar dados fictícios ou devidamente anonimizados.

## Tecnologias utilizadas

As tecnologias e ferramentas serão documentadas nesta seção após a definição da arquitetura técnica do projeto.

| Categoria | Tecnologia |
|---|---|
| Front-end | A definir |
| Back-end | A definir |
| Banco de dados | A definir |
| Autenticação | A definir |
| Hospedagem | A definir |
| Controle de versão | Git e GitHub |

## Organização do repositório

A estrutura abaixo é uma proposta inicial e poderá ser adaptada conforme a arquitetura escolhida:

```text
sistema-gestao-terapeutica-infantil/
├── README.md
├── docs/
│   ├── requisitos.md
│   ├── regras-de-negocio.md
│   ├── arquitetura.md
│   └── diagramas/
├── src/
│   └── ...
├── tests/
│   └── ...
└── .gitignore
```

- `README.md`: apresentação, objetivos e informações gerais do projeto.
- `docs/`: documentação funcional, técnica e diagramas.
- `src/`: código-fonte da aplicação.
- `tests/`: testes automatizados e outros testes do sistema.
- `.gitignore`: arquivos e diretórios que não devem ser versionados.

A estrutura definitiva será estabelecida após a escolha das tecnologias.

## Critérios de sucesso

O sistema será considerado alinhado aos objetivos iniciais quando:

- Os agendamentos recorrentes permanecerem consistentes.
- Alterações futuras não modificarem indevidamente atendimentos anteriores.
- O sistema impedir conflitos de horários para o mesmo profissional.
- Os profissionais conseguirem consultar suas agendas e pacientes vinculados.
- Os relatórios forem associados aos pacientes e atendimentos corretos.
- A administração conseguir gerenciar comunicados e configurações.
- O cálculo da produção mensal corresponder às regras aprovadas.
- Os usuários acessarem somente as informações autorizadas.
- A administração conseguir consultar as duas unidades conforme as permissões definidas.
- Os registros importantes forem preservados e facilmente consultados.

## Pendências para validação com a clínica

Antes da implementação definitiva, será necessário confirmar:

- As regras de cálculo da produção dos profissionais.
- As modalidades de atendimento oferecidas.
- As permissões de acesso entre as unidades.
- As informações que deverão constar nos relatórios clínicos.
- Os critérios de acesso aos registros clínicos.
- As regras de cancelamento, falta e remarcação.
- Os procedimentos de consentimento, proteção e guarda dos dados.
- A necessidade de exportação de relatórios.
- A infraestrutura de hospedagem, backup e manutenção.

## Metodologia de desenvolvimento

O projeto será desenvolvido de maneira incremental, priorizando as funcionalidades essenciais, a validação dos requisitos com a clínica e a realização de testes antes da disponibilização de cada recurso.

O Git e o GitHub serão utilizados para controle de versão, organização do código, documentação e colaboração entre as desenvolvedoras.

## Equipe

Projeto desenvolvido em colaboração por:

- **Camilla Vitoria** — Desenvolvimento de software.
- **Jéssica Maria** — Desenvolvimento de software.


## Considerações finais

O Sistema de Gestão de Atendimentos Terapêuticos Infantis tem como propósito oferecer uma solução centralizada para melhorar a organização, a eficiência e a rastreabilidade das atividades da clínica.

Com uma área exclusiva para os profissionais, ferramentas administrativas e financeiras e suporte à gestão de duas unidades, o sistema será estruturado para atender às necessidades essenciais da operação e permitir evoluções futuras de forma organizada e segura.

---

**Status do projeto:** Em planejamento e desenvolvimento.

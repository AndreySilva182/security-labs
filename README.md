
# 🔐 Security Labs — Laboratórios Práticos de Segurança da Informação

Repositório dedicado ao desenvolvimento de laboratórios práticos de **Cybersecurity**, com foco em auditoria de segurança, gerenciamento de vulnerabilidades, controle de acesso, hardening, monitoramento e resposta a incidentes.

O projeto tem como objetivo aplicar conhecimentos técnicos em ambientes virtualizados, documentando procedimentos, ferramentas, resultados e evidências.

---

## 🎯 Objetivo do projeto

Desenvolver habilidades práticas de Segurança da Informação por meio da execução de laboratórios que simulam atividades realizadas por profissionais de infraestrutura, segurança defensiva e operações de segurança (SOC).

### Competências abordadas

- Security Auditing
- Vulnerability Management
- Identity and Access Management (IAM)
- Linux Hardening
- Security Monitoring
- Incident Detection
- Incident Response
- Security Documentation

---

## 🖥️ Ambiente e tecnologias

| Tecnologia | Aplicação |
|---|---|
| Ubuntu Linux | Sistema operacional dos laboratórios |
| VMware Workstation | Virtualização dos ambientes |
| Lynis | Auditoria e avaliação de segurança |
| APT | Gerenciamento de pacotes e atualizações |
| Nessus | Avaliação de vulnerabilidades (planejado) |
| Wazuh | Monitoramento de segurança (planejado) |
| Linux Audit Framework | Auditoria de eventos (planejado) |
| GitHub | Documentação técnica e evidências |

As ferramentas poderão ser ampliadas conforme a evolução dos laboratórios.

---

## 📚 Laboratórios

| Nº | Laboratório | Status |
|---|---|---|
| 01 | Auditoria de Segurança com Lynis | ✅ Concluído |
| 02 | Gerenciamento de Vulnerabilidades | ⏳ Planejado |
| 03 | Controle de Acesso e Permissões | ⏳ Planejado |
| 04 | Hardening de Sistemas Linux | ⏳ Planejado |
| 05 | Monitoramento de Segurança com Wazuh | ⏳ Planejado |
| 06 | Detecção e Investigação de Incidentes | ⏳ Planejado |
| 07 | Resposta a Incidentes | ⏳ Planejado |

---

## ✅ Laboratório 01 — Auditoria de Segurança com Lynis

**Objetivo:** realizar uma auditoria em um sistema Ubuntu Linux, identificar atualizações de segurança pendentes, aplicar correções e validar os resultados.

### Atividades realizadas

- Execução de auditoria com Lynis;
- Análise de alertas e recomendações;
- Identificação de atualizações de segurança;
- Investigação do alerta PKGS-7392;
- Atualização de pacotes e do kernel Linux;
- Aplicação de medidas de remediação;
- Validação dos resultados após as correções.

### Resultados obtidos

| Indicador | Inicial | Final |
|---|---|---|
| Hardening Index | 61 | 67 |
| Testes executados | 250 | 250 |
| Atualizações de segurança detectadas | 11 | 0 |
| Alerta PKGS-7392 | Identificado | Não identificado na validação final |
| Kernel Linux | 7.0.0-31 | 7.0.0-42 |

O laboratório demonstrou a importância de investigar alertas, aplicar atualizações e validar a eficácia das medidas adotadas.

📂 **[Acessar documentação completa do Laboratório 01](lab-01-auditoria-lynis/README.md)**

---

## 🔎 Metodologia

Os laboratórios seguem uma metodologia baseada em cinco etapas:

1. **Planejamento:** definição do objetivo e preparação do ambiente.
2. **Execução:** utilização prática de ferramentas e comandos.
3. **Análise:** interpretação dos resultados identificados.
4. **Validação:** verificação dos procedimentos e das correções.
5. **Documentação:** registro técnico das atividades e evidências.

Todos os testes são realizados em ambientes próprios e autorizados, destinados ao aprendizado.

---

## 📁 Organização do repositório

security-labs/
│
├── README.md
│
├── lab-01-auditoria-lynis/
│   ├── README.md
│   └── evidencias/
│
├── lab-02-vulnerability-management/ (planejado)
├── lab-03-access-control/ (planejado)
├── lab-04-linux-hardening/ (planejado)
├── lab-05-security-monitoring/ (planejado)
├── lab-06-incident-detection/ (planejado)
└── lab-07-incident-response/ (planejado)

Cada laboratório terá sua própria documentação, incluindo objetivos, procedimentos, comandos utilizados, resultados e evidências.

---

## 🚀 Evolução do projeto

Este repositório faz parte do meu desenvolvimento profissional na área de Tecnologia da Informação, com foco no aprimoramento de competências em Segurança da Informação.

Os laboratórios serão desenvolvidos progressivamente, priorizando a compreensão dos procedimentos, a aplicação prática e a documentação técnica das atividades.

---

## 📌 Status do projeto

**Em desenvolvimento — 1 de 7 laboratórios concluído.**

Os próximos conteúdos serão adicionados conforme a execução e validação de cada laboratório.

---

**Security Labs | Hands-on Cybersecurity Portfolio**

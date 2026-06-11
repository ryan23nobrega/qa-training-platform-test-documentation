# Plano de Testes (Test Plan)

## 1. Introdução

Este documento descreve o planejamento de testes do projeto **QA Training Platform**, definindo escopo, abordagem, recursos, cronograma, riscos e critérios de aceite.

---

## 2. Objetivo

* Planejar atividades de teste do sistema
* Garantir cobertura adequada dos requisitos
* Minimizar riscos de falhas em produção
* Definir responsabilidades e escopo do QA
* Apoiar a tomada de decisão sobre qualidade do produto

---

## 3. Escopo dos Testes

### 3.1 Funcionalidades incluídas

* Login e autenticação
* Cadastro de usuários
* Cadastro de cursos
* Matrículas
* Emissão de certificados
* Relatórios

### 3.2 Funcionalidades excluídas

* Integrações externas
* Aplicativo mobile
* Infraestrutura e deploy

---

## 4. Itens a serem testados

* Funcionalidades do sistema
* Regras de negócio
* Controle de acesso por perfil
* Fluxos principais do usuário
* Validações de campos
* Mensagens de erro

---

## 5. Estratégia de Testes

A estratégia segue abordagem **Risk-Based Testing**, priorizando:

* Fluxos críticos (login, matrícula, certificação)
* Funcionalidades com impacto no negócio
* Áreas com maior complexidade

---

## 6. Tipos de Testes

* Testes Funcionais
* Testes de Regressão
* Testes de Integração
* Testes de UI
* Testes Exploratórios (limitado)

---

## 7. Ambientes de Teste

* Ambiente de Desenvolvimento (DEV)
* Ambiente de Homologação (HML)

---

## 8. Critérios de Entrada

* Requisitos aprovados e versionados
* Ambiente estável disponível
* Dados de teste preparados
* Build liberado para QA

---

## 9. Critérios de Saída

* 100% dos testes planejados executados
* 0 bugs críticos em aberto
* Bugs de alta severidade tratados
* Aprovação do fluxo principal do sistema

---

## 10. Recursos

* 1 QA responsável (simulado)
* Ferramenta de documentação: Markdown
* Repositório: GitHub

---

## 11. Cronograma de Testes

| Fase         | Descrição                          | Duração |
| ------------ | ---------------------------------- | ------- |
| Análise      | Revisão de requisitos              | 1 dia   |
| Planejamento | Criação de casos de teste          | 2 dias  |
| Execução     | Execução dos testes                | 3 dias  |
| Reporte      | Registro de bugs e relatório final | 1 dia   |

---

## 12. Riscos

| Risco                     | Impacto | Mitigação                    |
| ------------------------- | ------- | ---------------------------- |
| Mudança de requisitos     | Alto    | Reavaliação contínua         |
| Ambiente instável         | Alto    | Validação prévia             |
| Dados inconsistentes      | Médio   | Preparação de massa de teste |
| Atraso no desenvolvimento | Médio   | Replanejamento de testes     |

---

## 13. Métricas de Qualidade

* Percentual de execução de testes
* Taxa de aprovação (Pass Rate)
* Número de defeitos por módulo
* Severidade dos defeitos encontrados

---

## 14. Aprovação

Este plano deve ser revisado e aprovado antes do início da execução dos testes.

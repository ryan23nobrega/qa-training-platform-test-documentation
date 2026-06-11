# Estratégia de Testes (Test Strategy)

## 1. Introdução

Este documento define a estratégia de testes para o projeto **QA Training Platform**, descrevendo abordagens, tipos de testes, níveis, técnicas e critérios utilizados para garantir a qualidade do sistema.

---

## 2. Objetivo da Estratégia

* Definir abordagem de testes do projeto
* Garantir cobertura adequada dos requisitos
* Reduzir riscos de falhas em produção
* Padronizar atividades de QA
* Servir como base para planejamento e execução

---

## 3. Escopo de Testes

### Funcionalidades cobertas:

* Login e autenticação
* Cadastro de usuários
* Cadastro de cursos
* Matrículas
* Emissão de certificados
* Relatórios

### Fora do escopo:

* Integrações externas
* Testes de performance avançados (carga massiva)
* Aplicativo mobile

---

## 4. Tipos de Testes

### 4.1 Testes Funcionais

Validação dos requisitos funcionais do sistema.

### 4.2 Testes de Regressão

Garantia de que novas alterações não quebrem funcionalidades existentes.

### 4.3 Testes de Integração

Validação da comunicação entre módulos (ex: matrícula → curso → certificado).

### 4.4 Testes de Interface (UI)

Validação da usabilidade e comportamento visual.

### 4.5 Testes de Segurança (básico)

* Autenticação
* Controle de acesso
* Proteção de dados sensíveis

---

## 5. Técnicas de Teste Aplicadas

* Particionamento de Equivalência
* Análise de Valor Limite
* Tabela de Decisão
* Transição de Estado
* Adivinhação de Erros (Error Guessing)

---

## 6. Níveis de Teste

* Testes de Sistema
* Testes de Integração
* Testes de Aceitação (UAT simulado)

---

## 7. Critérios de Entrada

* Requisitos documentados e aprovados
* Ambiente de teste disponível
* Build estável entregue
* Dados de teste preparados

---

## 8. Critérios de Saída

* 100% dos casos de teste executados
* 0 bugs críticos abertos
* Bugs de alta severidade resolvidos ou mitigados
* Aprovação do fluxo principal

---

## 9. Riscos

* Mudanças frequentes de requisitos
* Ambientes instáveis
* Dados de teste inconsistentes
* Dependência de terceiros (futuro)

---

## 10. Ferramentas (simuladas)

* Documentação: Markdown
* Gestão: GitHub
* Testes (futuro): Postman / Playwright
* Métricas: Excel / Sheets

---

## 11. Abordagem Geral

A abordagem adotada é **Risk-Based Testing**, priorizando fluxos críticos como:

* Login
* Matrícula
* Certificação

Fluxos secundários são testados após validação dos principais.

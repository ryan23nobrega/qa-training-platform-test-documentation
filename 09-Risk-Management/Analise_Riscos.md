# Análise e Gestão de Riscos

## Projeto

QA Training Platform

---

## 1. Objetivo

Identificar, analisar e mitigar riscos que possam impactar a qualidade do sistema, cronograma ou experiência do usuário.

---

## 2. Metodologia

A análise de riscos é baseada em:

* Probabilidade de ocorrência
* Impacto no negócio
* Criticidade do fluxo afetado

Classificação:

* Baixo
* Médio
* Alto

---

## 3. Matriz de Riscos

| Risco                       | Descrição                            | Probabilidade | Impacto | Nível |
| --------------------------- | ------------------------------------ | ------------- | ------- | ----- |
| Falha de autenticação       | Usuários não conseguirem logar       | Média         | Alto    | Alto  |
| Duplicidade de cadastro     | Usuários duplicados no sistema       | Alta          | Alto    | Alto  |
| Instabilidade em matrículas | Falhas ao matricular em cursos       | Média         | Alto    | Alto  |
| Dados inconsistentes        | Informações incorretas em relatórios | Média         | Médio   | Médio |
| Performance degradada       | Sistema lento com muitos usuários    | Baixa         | Alto    | Médio |
| Erros em regras de negócio  | Validações incorretas                | Média         | Alto    | Alto  |

---

## 4. Análise de Impacto

### Alto impacto:

* Login
* Matrículas
* Cadastro de usuários

### Médio impacto:

* Relatórios
* Consultas gerais

### Baixo impacto:

* Ajustes de interface

---

## 5. Estratégias de Mitigação

* Implementação de testes automatizados nos fluxos críticos
* Revisão de regras de negócio com stakeholders
* Execução de testes de regressão contínuos
* Validação de dados de entrada
* Monitoramento de logs em ambiente de teste

---

## 6. Riscos Não Mitigados

* Integrações futuras externas não testadas
* Possíveis falhas em ambientes de produção não simulados

---

## 7. Conclusão

A maioria dos riscos identificados está relacionada a fluxos críticos do sistema, exigindo maior atenção da equipe de QA para garantir estabilidade e confiabilidade antes da liberação em produção.

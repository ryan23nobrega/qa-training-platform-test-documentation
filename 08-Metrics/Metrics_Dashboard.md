# Métricas de Qualidade (QA Metrics Dashboard)

## Projeto

QA Training Platform

---

## 1. Objetivo

Definir e acompanhar indicadores de qualidade do processo de testes, permitindo análise de eficiência, cobertura e estabilidade do sistema.

---

## 2. Métricas Gerais do Ciclo

| Métrica                     | Valor |
| --------------------------- | ----- |
| Casos de Teste Planejados   | 14    |
| Casos Executados            | 14    |
| Casos Aprovados             | 10    |
| Casos Reprovados            | 4     |
| Taxa de Sucesso (Pass Rate) | 71%   |
| Cobertura de Requisitos     | 58%   |

---

## 3. Defect Metrics

| Métrica           | Valor               |
| ----------------- | ------------------- |
| Total de Defeitos | 4                   |
| Defeitos Críticos | 2                   |
| Defeitos Médios   | 2                   |
| Defeitos Baixos   | 0                   |
| Defect Density    | 0.28 defeitos/teste |

---

## 4. Análise de Severidade

| Severidade | Quantidade |
| ---------- | ---------- |
| Alta       | 2          |
| Média      | 2          |
| Baixa      | 0          |

---

## 5. Qualidade do Produto

* Fluxos críticos apresentam falhas em validações de regras de negócio
* Autenticação apresenta comportamento inconsistente
* Cadastro de dados apresenta problemas de duplicidade
* Sistema ainda não atende critérios de estabilidade para produção

---

## 6. Tendência de Qualidade (Simulação)

| Ciclo    | Pass Rate      |
| -------- | -------------- |
| Sprint 1 | 71%            |
| Sprint 2 | (esperado 85%) |
| Sprint 3 | (esperado 95%) |

---

## 7. Indicadores TMMi

### Nível de Maturidade Atual (simulado):

* Nível 2: Managed ✔
* Nível 3: Defined ✔ (parcial)
* Nível 4: Measurement ✔ (em implementação)
* Nível 5: Optimization ✖

---

## 8. Conclusão

As métricas indicam que o sistema ainda está em fase de estabilização. É necessário reduzir defeitos críticos e aumentar cobertura de testes antes de evolução para produção.

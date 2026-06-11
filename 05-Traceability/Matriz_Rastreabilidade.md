# Matriz de Rastreabilidade de Requisitos

## Objetivo

Garantir que todos os requisitos funcionais estejam cobertos por casos de teste, assegurando rastreabilidade entre negócio e validação.

---

## Legenda

* RF = Requisito Funcional
* CT = Caso de Teste

---

## Matriz de Rastreabilidade

| Requisito | Descrição                   | Casos de Teste                         | Status de Cobertura |
| --------- | --------------------------- | -------------------------------------- | ------------------- |
| RF-001    | Login no sistema            | CT-001, CT-002, CT-003, CT-004 (Login) | Coberto             |
| RF-002    | Recuperação de senha        | (a criar)                              | Parcial             |
| RF-003    | Cadastro de usuários        | CT-001, CT-002 (Cadastro de Usuários)  | Coberto             |
| RF-004    | Edição de usuários          | (a criar)                              | Não coberto         |
| RF-005    | Exclusão de usuários        | (a criar)                              | Não coberto         |
| RF-006    | Cadastro de cursos          | CT-001, CT-002 (Cursos)                | Coberto             |
| RF-007    | Edição de cursos            | (a criar)                              | Não coberto         |
| RF-008    | Matrícula em cursos         | CT-001, CT-002 (Matrículas)            | Coberto             |
| RF-009    | Acompanhamento de progresso | (a criar)                              | Não coberto         |
| RF-010    | Emissão de certificados     | (a criar)                              | Não coberto         |
| RF-011    | Relatórios gerenciais       | (a criar)                              | Não coberto         |
| RF-012    | Controle de perfis          | (a criar)                              | Não coberto         |

---

## Análise de Cobertura

### Cobertura atual:

* Funcionalidades críticas: ~50%
* Funcionalidades secundárias: 0%

### Observação:

Este projeto está em fase inicial de construção de suíte de testes.

---

## Próximos passos

* Criar casos de teste para RFs não cobertos
* Expandir cenários negativos
* Incluir testes de segurança e permissão

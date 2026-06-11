# Gestão de Defeitos (Defect Management)

## Objetivo

Documentar, classificar e acompanhar defeitos encontrados durante a execução dos testes, garantindo rastreabilidade e clareza para correção.

---

## Legenda

* **Severidade:** Impacto técnico/negócio do defeito
* **Prioridade:** Urgência de correção

---

## BUG-001 - Login permite senha incorreta

**Severidade:** Alta
**Prioridade:** Alta

### Descrição

O sistema permite autenticação mesmo quando a senha está incorreta em determinadas tentativas intermitentes.

### Passos para reproduzir

1. Acessar tela de login
2. Inserir e-mail válido
3. Inserir senha incorreta
4. Clicar em entrar

### Resultado atual

Usuário é autenticado incorretamente

### Resultado esperado

Sistema deve bloquear acesso e exibir mensagem de erro

---

## BUG-002 - Cadastro permite e-mail duplicado

**Severidade:** Alta
**Prioridade:** Alta

### Descrição

Sistema permite criação de dois usuários com o mesmo e-mail.

### Passos para reproduzir

1. Acessar cadastro de usuários
2. Criar usuário com e-mail X
3. Repetir cadastro com mesmo e-mail

### Resultado atual

Sistema permite duplicidade

### Resultado esperado

Sistema deve impedir cadastro duplicado

---

## BUG-003 - Curso com carga horária inválida

**Severidade:** Média
**Prioridade:** Média

### Descrição

Sistema permite cadastro de curso com carga horária zero ou negativa.

### Passos para reproduzir

1. Acessar cadastro de curso
2. Informar carga horária = 0 ou -10
3. Salvar

### Resultado atual

Curso é criado com valor inválido

### Resultado esperado

Sistema deve validar e impedir cadastro

---

## BUG-004 - Matrícula duplicada não bloqueada

**Severidade:** Média
**Prioridade:** Alta

### Descrição

Usuário consegue se matricular múltiplas vezes no mesmo curso.

### Passos para reproduzir

1. Selecionar curso
2. Realizar matrícula
3. Repetir matrícula no mesmo curso

### Resultado atual

Sistema permite duplicidade de matrícula

### Resultado esperado

Sistema deve bloquear matrícula repetida

---

## Observações Gerais

* Bugs simulados baseados em cenários comuns de sistemas corporativos
* Usados para demonstrar capacidade de análise e documentação de defeitos

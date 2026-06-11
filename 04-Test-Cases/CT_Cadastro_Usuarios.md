# Casos de Teste - Cadastro de Usuários

## CT-001 - Cadastro de usuário válido

**Pré-condição:**
Usuário administrador autenticado

**Passos:**

1. Acessar tela de cadastro de usuários
2. Informar nome válido
3. Informar e-mail válido
4. Informar senha válida
5. Salvar

**Resultado esperado:**
Usuário deve ser criado com sucesso

---

## CT-002 - E-mail duplicado

**Passos:**

1. Acessar cadastro
2. Informar e-mail já existente
3. Preencher demais campos válidos
4. Salvar

**Resultado esperado:**
Sistema deve impedir cadastro duplicado

---

## CT-003 - Campos obrigatórios vazios

**Resultado esperado:**
Sistema deve bloquear cadastro e exibir mensagens de validação

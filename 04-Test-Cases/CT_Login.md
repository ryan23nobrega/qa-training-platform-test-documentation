# Casos de Teste - Login

## CT-001 - Login com credenciais válidas

**Pré-condição:**
Usuário cadastrado no sistema

**Passos:**

1. Acessar tela de login
2. Inserir e-mail válido
3. Inserir senha válida
4. Clicar em "Entrar"

**Resultado esperado:**
Usuário deve ser autenticado com sucesso e redirecionado para o dashboard

---

## CT-002 - Login com senha inválida

**Pré-condição:**
Usuário cadastrado

**Passos:**

1. Acessar tela de login
2. Inserir e-mail válido
3. Inserir senha incorreta
4. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve exibir mensagem de erro "Credenciais inválidas"

---

## CT-003 - Login com e-mail não cadastrado

**Passos:**

1. Acessar tela de login
2. Inserir e-mail inexistente
3. Inserir senha qualquer
4. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve impedir login e exibir mensagem de usuário não encontrado

---

## CT-004 - Campos obrigatórios vazios

**Passos:**

1. Acessar tela de login
2. Deixar e-mail vazio
3. Deixar senha vazia
4. Clicar em "Entrar"

**Resultado esperado:**
Sistema deve validar campos obrigatórios e impedir envio

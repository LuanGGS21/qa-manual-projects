Casos de Teste – Login

CT-001 – Login com credenciais válidas
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar a página de login
2. Inserir e-mail válido
3. Inserir senha válida
4. Clicar em "Entrar"

**Resultado esperado:** Usuário autenticado com sucesso
**Resultado obtido:** Login realizado com sucesso

---

CT-002 – Login com senha inválida
**Passos:**
1. Acessar login
2. Inserir e-mail válido
3. Inserir senha inválida
4. Clicar em "Entrar"

**Resultado esperado:** Mensagem de erro informando credenciais inválidas
**Resultado obtido:** Login não realizado, mostrada mensagem de erro

---

CT-003 – Campos vazios
**Passos:**
1. Acessar login
2. Não preencher campos
3. Clicar em "Entrar"

**Resultado esperado:** Sistema impede login e exibe mensagem de validação
**Resultado obtido:** Login não realizado, impedido pelo sistema

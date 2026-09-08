# Casos de Teste Step-by-Step

## CT-001: Login com Credenciais Válidas

| ID             | CT-001                        |
| -------------- | ----------------------------- |
| **Título**     | Login com credenciais válidas |
| **User Story** | US-001 - Login do Cliente     |
| **Prioridade** | High                          |
| **Tipo**       | Funcional                     |

### Pré-condição

- Usuário está na página de login
- Credenciais válidas cadastradas

### Passos

| Passo | Ação                  | Dado Esperado    |
| ----- | --------------------- | ---------------- |
| 1     | Digitar email válido  | email@teste.com  |
| 2     | Digitar senha correta | senha123         |
| 3     | Clicar em "Entrar"    | Redirecionamento |

### Resultado Esperado

Login realizado com sucesso, usuário redirecionado para página inicial.

---

## CT-002: Login com Senha Incorreta

| ID             | CT-002                    |
| -------------- | ------------------------- |
| **Título**     | Login com senha incorreta |
| **User Story** | US-001 - Login do Cliente |
| **Prioridade** | High                      |
| **Tipo**       | Funcional / Negativo      |

### Pré-condição

- Usuário está na página de login

### Passos

| Passo | Ação                    | Dado Esperado    |
| ----- | ----------------------- | ---------------- |
| 1     | Digitar email válido    | email@teste.com  |
| 2     | Digitar senha incorreta | senha_errada     |
| 3     | Clicar em "Entrar"      | Mensagem de erro |

### Resultado Esperado

Mensagem "Credenciais inválidas" exibida, usuário permanece na página de login.

# Casos de Teste BDD (Gherkin)

## Caso 1: Login com Sucesso

```gherkin
# language: pt

Funcionalidade: Login do Cliente
  Como um cliente registrado
  Eu quero fazer login no sistema
  Para acessar minha conta e realizar compras

  Cenário: Login com credenciais válidas
    Dado que o usuário está na página de login
    E possui um cadastro ativo
    Quando preenche o campo "Email" com "joao@email.com"
    E preenche o campo "Senha" com "Joao@123"
    E clica no botão "Entrar"
    Então o sistema deve redirecionar para página inicial
    E deve exibir "Olá, João" no cabeçalho
    E o botão "Entrar" deve ser substituído por "Sair"
```

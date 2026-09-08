# User Stories

## User Story 1: Login do Cliente

**Título:** Como usuário, quero fazer login no sistema para acessar minha conta

**Descrição:**

> Como um **cliente registrado**  
> Eu quero **fazer login no sistema**  
> Para que eu possa **visualizar meu histórico de pedidos e realizar compras**

**Critérios de Aceitação:**

- [ ] Campo "Email" deve aceitar formato válido (usuario@dominio.com)
- [ ] Campo "Senha" deve ser do tipo password (oculto)
- [ ] Login bem-sucedido redireciona para página inicial
- [ ] Login inválido exibe mensagem "Credenciais inválidas"
- [ ] Após 5 tentativas falhas, conta bloqueada por 15 minutos

**Prioridade:** High  
**Labels:** feature, login, security

---

## User Story 2: Adicionar Produto ao Carrinho

**Título:** Como usuário, quero adicionar produtos ao carrinho para finalizar compra

**Descrição:**

> Como um **cliente navegando na loja**  
> Eu quero **adicionar produtos ao carrinho de compras**  
> Para que eu possa **revisar meus itens antes de finalizar a compra**

**Critérios de Aceitação:**

- [ ] Cada produto deve ter botão "Adicionar ao Carrinho"
- [ ] Ao adicionar, deve aparecer notificação de confirmação
- [ ] Carrinho deve atualizar automaticamente o total
- [ ] É possível remover itens individualmente
- [ ] Carrinho vazio exibe "Seu carrinho está vazio"

**Prioridade:** High  
**Labels:** feature, cart, e-commerce

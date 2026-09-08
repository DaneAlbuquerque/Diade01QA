# Mind-map - User Story de Login

## Diagrama

![Mind-map Login](/images/mindmap_login.png)

## Descrição dos Galhos

### VALIDAÇÃO

- **Email:** Formato válido (usuario@dominio.com), Máx: 100 caracteres
- **Senha:** Mín: 6 caracteres, Caracteres especiais (@!#$%)

### SEGURANÇA

- 5 tentativas erradas → Bloqueio por 15 minutos
- Senha mascarada (••••••••)
- Conexão HTTPS

### USABILIDADE

- Botão "Entrar" visível
- Link "Esqueci minha senha"
- Redireciona para página inicial

### PERFORMANCE

- Resposta do login < 2 segundos
- Carregamento pós-login < 3 segundos

### TESTES NEGATIVOS

- SQL Injection: ' OR '1'='1
- XSS: <script>alert('XSS')</script>
- Força bruta: 100 tentativas em 1 minuto

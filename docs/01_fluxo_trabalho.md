# Fluxo de Trabalho no Jira

## Workflow do Ciclo de Vida do Bug

O workflow foi configurado no Jira com os seguintes status e transições:

### Status

| Status      | Descrição                         | Responsável   |
| ----------- | --------------------------------- | ------------- |
| NOVO        | Bug reportado, aguardando análise | QA/Usuário    |
| EM ANÁLISE  | Equipe analisando o bug           | Desenvolvedor |
| EM CORREÇÃO | Bug sendo corrigido               | Desenvolvedor |
| CORRIGIDO   | Bug corrigido, aguardando teste   | Desenvolvedor |
| EM RETESTE  | QA testando a correção            | QA            |
| REABERTO    | Bug persiste, volta para correção | QA            |
| FECHADO     | Bug corrigido e aprovado          | QA            |

### Transições

| De          | Para        | Transição             |
| ----------- | ----------- | --------------------- |
| NOVO        | EM ANÁLISE  | Iniciar Análise       |
| EM ANÁLISE  | EM CORREÇÃO | Aprovar Correção      |
| EM CORREÇÃO | CORRIGIDO   | Finalizar Correção    |
| CORRIGIDO   | EM RETESTE  | Enviar para QA        |
| EM RETESTE  | FECHADO     | Aprovar Bug           |
| EM RETESTE  | REABERTO    | Bug Persiste          |
| REABERTO    | EM CORREÇÃO | Reabrir para Correção |

### Diagrama do Workflow

![Workflow do Jira](/jira/evidencias_jira/09_workflow_completo.png)

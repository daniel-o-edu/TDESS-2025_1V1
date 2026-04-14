**Título:** Erro 500 ao enviar formulário com CEP vazio.
**Categoria:** Interface/Validação | **Severidade:** Grave | **Prioridade:** Alta

**Precondição:** Estar autenticado na tela de "Novo Endereço".

**Passos para Reprodução:**
1. Acessar a tela de cadastro de cliente.
2. Preencher os campos "Nome" e "Rua", deixando "CEP" em branco.
3. Clicar no botão "Salvar".

**Resultado Esperado:** Sistema deve bloquear o envio e exibir "CEP obrigatório".
**Resultado Obtido:** Sistema trava e exibe tela em branco com código HTTP 500.
**Evidências:** [link-screenshot-log-console.png]


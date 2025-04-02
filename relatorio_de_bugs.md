# Relatório de Bug  

**Título:** Erro ao tentar recuperar senha com e-mail inválido.  
**Severidade:** Média  
**Prioridade:** Alta  
**Passos para reproduzir:**  
1. Acessar a página de recuperação de senha.  
2. Inserir um e-mail inválido (ex: `usuario@teste`).  
3. Clicar no botão "Recuperar senha".  

**Resultado Esperado:** O sistema deve exibir uma mensagem informando que o e-mail é inválido.  
**Resultado Obtido:** O sistema exibe erro 500 (Internal Server Error).  

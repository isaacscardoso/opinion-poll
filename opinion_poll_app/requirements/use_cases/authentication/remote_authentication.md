# Remote Authentication Use Case

> ## Caso de Sucesso
1. ✅ O sistema valida os dados
2. ✅ O sistema faz uma requisição para a URL da API de login
3. ✅ O sistema valida os dados recebidos da API
4. ✅ O sistema entrega os dados da conta do usuário

> ## Exceção - URL inválida (404 Not Found)
1. ✅ O sistema retorna uma mensagem de erro inesperado

> ## Exceção - Dados inválidos (400 Bad Request)
1. ✅ O sistema retorna uma mensagem de erro inesperado

> ## Exceção - Resposta inválida (502 Bad Gateway)
1. ✅ O sistema retorna uma mensagem de erro inesperado

> ## Exceção - Falha no servidor (500 Internal Server Error)
1. ✅ O sistema retorna uma mensagem de erro inesperado

> ## Exceção - Credenciais inválidas (401 Unauthorized)
1. ✅ O sistema retorna uma mensagem de erro informando que as credenciais estão erradas
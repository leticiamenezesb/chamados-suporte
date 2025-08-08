# Chamado: Falha no login - credenciais inválidas

**Data da abertura:** 07/08/2025  
**Status:** Aberto  
**Prioridade:** Alta  
**Responsável:** Equipe de Desenvolvimento

---

## Descrição do problema  
Usuário reporta que não consegue acessar o sistema mesmo informando credenciais corretas.

![Erro Login](https://via.placeholder.com/400x200.png?text=Erro+Login)

**Mensagem exibida:**  
Erro: Usuário ou senha inválidos

---

## Passos para reproduzir  
1. Acessar a página de login.  
2. Informar usuário joao.silva e senha correta.  
3. Clicar em **Entrar**.

---

## Resultado atual  
Mensagem de credenciais inválidas exibida.

---

## Resultado esperado  
Login realizado com sucesso.

---

## Análise inicial  
Possível problema de sincronização na base de dados ou falha no serviço de autenticação.

---

## Próximos passos  
- Verificar logs do serviço de autenticação.  
- Testar credenciais diretamente na API.  
- Retestar após ajuste.

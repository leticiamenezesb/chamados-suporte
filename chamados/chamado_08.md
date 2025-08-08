# Chamado: Erro de permissão ao acessar área restrita

**Data da abertura:** 31/07/2025  
**Status:** Aberto  
**Prioridade:** Alta  
**Responsável:** Equipe de Segurança

---

## Descrição do problema  
Usuários com permissão correta não conseguem acessar área restrita do sistema.

![Erro Permissão](https://via.placeholder.com/400x200.png?text=Erro+Permissão)

**Mensagem exibida:**  
Erro: Acesso negado.

---

## Passos para reproduzir  
1. Login com usuário autorizado.  
2. Tentar acessar área restrita.  
3. Observar mensagem de acesso negado.

---

## Resultado atual  
Acesso negado mesmo com permissão.

---

## Resultado esperado  
Acesso liberado para usuários autorizados.

---

## Análise inicial  
Possível problema na verificação de permissões.

---

## Próximos passos  
- Revisar regras de permissão.  
- Testar permissões no ambiente de homologação.  
- Corrigir regras e deploy.

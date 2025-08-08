# Chamado: Página de cadastro apresenta erro 500

**Data da abertura:** 06/08/2025  
**Status:** Em andamento  
**Prioridade:** Média  
**Responsável:** Equipe de Backend

---

## Descrição do problema  
Ao tentar acessar a página de cadastro, o sistema retorna erro interno do servidor.

![Erro 500](https://via.placeholder.com/400x200.png?text=Erro+500)

**Mensagem exibida:**  
Erro 500 - Internal Server Error

---

## Passos para reproduzir  
1. Navegar até a página de cadastro.  
2. Preencher o formulário parcialmente.  
3. Clicar em **Enviar**.

---

## Resultado atual  
Página retorna erro 500.

---

## Resultado esperado  
Cadastro realizado normalmente ou validação de campos com mensagem clara.

---

## Análise inicial  
Erro pode estar relacionado a falha no endpoint que processa os dados do formulário.

---

## Próximos passos  
- Analisar logs do servidor.  
- Testar endpoint manualmente.  
- Corrigir possível exceção lançada.

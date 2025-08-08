# Chamado: Falha no upload de arquivos

**Data da abertura:** 28/07/2025  
**Status:** Fechado  
**Prioridade:** Média  
**Responsável:** Equipe Backend

---

## Descrição do problema  
Upload de arquivos está falhando para usuários com arquivos maiores que 5MB.

![Falha Upload](https://via.placeholder.com/400x200.png?text=Falha+Upload)

**Mensagem exibida:**  
Erro: Tamanho máximo de arquivo excedido.

---

## Passos para reproduzir  
1. Selecionar arquivo maior que 5MB.  
2. Tentar realizar upload.  
3. Receber mensagem de erro.

---

## Resultado atual  
Upload bloqueado para arquivos grandes.

---

## Resultado esperado  
Upload realizado com sucesso para arquivos dentro do limite.

---

## Análise inicial  
Limite de tamanho não configurado corretamente.

---

## Próximos passos  
- Ajustar limite de tamanho no servidor.  
- Testar upload novamente.  
- Validar no ambiente de produção.

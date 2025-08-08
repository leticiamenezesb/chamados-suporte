# Chamado: Erro na validação do formulário de contato

**Data da abertura:** 03/08/2025  
**Status:** Fechado  
**Prioridade:** Média  
**Responsável:** Equipe Frontend

---

## Descrição do problema  
Usuários não conseguem enviar o formulário de contato devido a erros de validação.

![Erro Formulário](https://via.placeholder.com/400x200.png?text=Erro+Formulário)

**Mensagem exibida:**  
Erro: Campo email obrigatório não preenchido.

---

## Passos para reproduzir  
1. Acessar página de contato.  
2. Preencher formulário sem informar email.  
3. Clicar em **Enviar**.

---

## Resultado atual  
Mensagem de erro de validação aparece mesmo quando email é informado.

---

## Resultado esperado  
Formulário enviado com sucesso após preenchimento correto.

---

## Análise inicial  
Bug no script de validação do formulário.

---

## Próximos passos  
- Corrigir script de validação.  
- Testar envio com dados válidos.  
- Validar no ambiente de homologação.

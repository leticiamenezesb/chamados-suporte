# Chamado: Timeout na API de consulta

**Data da abertura:** 04/08/2025  
**Status:** Aberto  
**Prioridade:** Alta  
**Responsável:** Equipe de API

---

## Descrição do problema  
Chamados relatam que as consultas via API estão demorando muito e resultando em timeout.

![Timeout API](https://via.placeholder.com/400x200.png?text=Timeout+API)

**Mensagem exibida:**  
Erro: Timeout ao tentar conectar com o servidor.

---

## Passos para reproduzir  
1. Enviar requisição GET para o endpoint /consulta.  
2. Aguardar resposta.  
3. Observar timeout após 30 segundos.

---

## Resultado atual  
Timeout após 30 segundos.

---

## Resultado esperado  
Resposta rápida com dados retornados em menos de 5 segundos.

---

## Análise inicial  
Pode ser problema de performance no serviço ou falha na rede.

---

## Próximos passos  
- Monitorar logs de rede.  
- Analisar performance da API.  
- Ajustar timeout e otimizar endpoint.

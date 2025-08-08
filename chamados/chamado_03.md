# Chamado: Lentidão na busca por produtos

**Data da abertura:** 05/08/2025  
**Status:** Aberto  
**Prioridade:** Baixa  
**Responsável:** Equipe de Infraestrutura

---

## Descrição do problema  
Usuários relatam demora excessiva ao realizar buscas na plataforma.

![Busca lenta](https://via.placeholder.com/400x200.png?text=Busca+Lenta)

---

## Passos para reproduzir  
1. Acessar a página de produtos.  
2. Digitar termo de busca, ex: "camiseta".  
3. Observar o tempo de resposta.

---

## Resultado atual  
Busca demora mais de 10 segundos para retornar resultados.

---

## Resultado esperado  
Resposta rápida, abaixo de 3 segundos.

---

## Análise inicial  
Possível problema de performance no banco de dados ou falta de cache.

---

## Próximos passos  
- Verificar índices do banco.  
- Avaliar utilização de cache.  
- Realizar testes de carga.

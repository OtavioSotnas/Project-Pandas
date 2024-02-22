# Análise Exploratória de Dados de Vendas Online - Módulo 2

## Por: Otávio, Tainah, Hugo e Daniel

**Objetivo:** aplicar os
conhecimentos adquiridos ao longo da disciplina de Técnicas de Programação 1 em
um contexto prático, relevante e data-driven.

**Base de dados**: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

**Trello:** https://trello.com/b/v8IAs6a9/trabalho-ada-tp1

**Compreendendo as bases de dados:**

![Tabela](https://github.com/OtavioSotnas/AnaliseExploratoria-ADA-Santander/assets/142911747/47beffb2-ed6b-44ff-ad7c-9899aa5b7cbe)


- **Order**: Este é o conjunto de dados principal. De cada pedido você pode encontrar todas as outras informações
- **Customers**: Informações sobre o cliente e sua localização.
- **Geolocation**: Informações dos CEPs e suas coordenadas lat/lng.
- **Order Items**: Dados sobre os itens adquiridos em cada pedido.
- **Payments**: Ddados sobre as opções de pagamento dos pedidos.
- **Order Reviews**: Dados sobre as avaliações feitas pelos clientes.
- **Products**: Dados sobre os produtos vendidos pelo site.
- **Sellers**: Dados sobre os vendedores que atenderam aos pedidos feitos no site.
 
 
 ## Seção para perguntas 
Deposite sua pergunta e deixe sua inicial na frente da pergunta:
- As maiores compras são feitas com cartão de crédito ? Se sim, Todas ou a maioria ?!
- Quais são os vendedores que mais atenderam pedidos ?
  - Quais os que atenderam mais de 100 pedidos
- Quais os produtos que são os produtos com maior preço no mercado ?
   - Quais os produtos que tem preço menor que a média do mercado
- Quais produtos têm avaliação boa e ruim? (usar ndarray para criarnova coluna com True e False)
  - Quais palavras mais usadas nos comentários com avaliações boas e ruins? (usar wordclouds)
- Como se distribuem os consumidores por estado?
- Quais as categorias de produtos mais propensas à insatisfação do cliente? (tentar fazer com merge).
- Calcular volume dos produtos (com ndarray).

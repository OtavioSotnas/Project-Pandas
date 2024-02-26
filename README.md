# Análise Exploratória de Dados de Vendas Online - Módulo 2

## Por: Otávio, Tainah, Hugo e Daniel

**Objetivo:** aplicar os
conhecimentos adquiridos ao longo da disciplina de Técnicas de Programação 1 em
um contexto prático, relevante e data-driven.

**Base de dados**: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

**Trello:** https://trello.com/b/v8IAs6a9/trabalho-ada-tp1

## Compreendendo as bases de dados

![Tabela](https://github.com/OtavioSotnas/AnaliseExploratoria-ADA-Santander/assets/142911747/47beffb2-ed6b-44ff-ad7c-9899aa5b7cbe)


- **Order**: Este é o conjunto de dados principal. De cada pedido você pode encontrar todas as outras informações
- **Customers**: Informações sobre o cliente e sua localização.
- **Geolocation**: Informações dos CEPs e suas coordenadas lat/lng.
- **Order Items**: Dados sobre os itens adquiridos em cada pedido.
- **Payments**: Ddados sobre as opções de pagamento dos pedidos.
- **Order Reviews**: Dados sobre as avaliações feitas pelos clientes.
- **Products**: Dados sobre os produtos vendidos pelo site.
- **Sellers**: Dados sobre os vendedores que atenderam aos pedidos feitos no site.
 
 
 ## Seção de perguntas 
- [x] Quais os tipos de pagamento mais utilizados? E para os valores mais altos, a proporção se mantém? (máscara booleana)
- [x] Quais tipos de pagamento permitem o parcelamento? (máscara booleana)
- [x] Verificar se um produto foi vendido acima do preço do mercado (ndarray)
- [x] Categorizar vendedores entre Iniciante, Intermediário, Avançado e Mestre (ndarray)
- [x] Quais estados que mais faturam ?
- [x] Quais estados faturam menos que a média ? (máscara booleana)
- [x] Quais produtos têm avaliação boa e ruim ? (usar ndarray para criarnova coluna com True e False)
- [x] Quais palavras mais usadas nos comentários com avaliações boas e ruins? (usar wordclouds)
- [x] Quais categorias de produtos com mais reclamações dos clientes ? (máscara booleana)
- [x] Qual o volume de cada produto em litros? (ndarray)
- [x] Como se distribuem os consumidores por estado?
- [x] Como se distribuem os consumidores por estado? (máscara booleana)

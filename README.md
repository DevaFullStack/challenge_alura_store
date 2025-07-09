# 🛍️ Análise de Desempenho das Lojas - Challenge Alura Store

Este projeto consiste em uma análise de dados do desempenho de quatro lojas, com o objetivo de identificar a loja com menor rendimento para auxiliar em uma decisão de negócio. O notebook explora diversas métricas, visualizações e uma análise geográfica para fornecer insights sobre a performance de cada unidade.

## ✨ Objetivo

O objetivo principal deste projeto é analisar os dados de vendas das Lojas 1, 2, 3 e 4 para calcular indicadores-chave de desempenho e determinar qual loja apresenta o menor rendimento geral. Os insights obtidos servirão como base para uma recomendação de negócio.

## 📊 Métricas Analisadas

As seguintes métricas foram calculadas e analisadas para cada loja:

- **Faturamento Total:** A receita bruta gerada por cada loja.
- **Faturamento Mensal:** A evolução do faturamento ao longo do tempo para identificar tendências e sazonalidade.
- **Vendas por Categoria de Produto:** Distribuição do faturamento entre as diferentes categorias de produtos em cada loja.
- **Avaliação Média dos Clientes:** Nível de satisfação dos clientes com base nas avaliações de compra.
- **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor saída em cada loja.
- **Frete Médio:** O custo médio de frete por venda em cada loja.
- **Análise Geográfica (Extra):** Visualização da distribuição espacial das vendas para identificar padrões regionais e áreas de concentração.

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python:** Linguagem de programação principal.
- **Pandas:** Para manipulação e análise de dados.
- **Matplotlib:** Para criação de gráficos estáticos.
- **Seaborn:** Para visualizações estatísticas (utilizado no Heatmap).
- **Squarify:** Para criação de Treemaps.
- **Folium:** Para criação de mapas interativos (Análise Geográfica Extra).

## 📂 Estrutura do Projeto

O projeto está organizado em um notebook Google Colab que segue as seguintes etapas:

1.  **Configuração Inicial:** Importação de bibliotecas e carregamento dos dados a partir de URLs públicas.
2.  **Carregamento e Consolidação dos Dados:** Leitura dos arquivos CSV de cada loja e combinação em um único DataFrame (`todas_lojas`).
3.  **Exploração Inicial dos Dados:** Verificação da estrutura, tipos de dados, e valores nulos.
4.  **Cálculo e Análise das Métricas:** Seção dedicada ao cálculo e exibição das métricas de desempenho para cada loja, acompanhadas de visualizações gráficas.
5.  **Análise Geográfica (Extra):** Exploração das coordenadas geográficas para visualizar a distribuição das vendas em mapas interativos.
6.  **Visualizações:** Geração de diversos tipos de gráficos para apresentar os resultados das análises de forma clara e compreensível.

## ▶️ Como Executar o Notebook

1.  Abra o arquivo do notebook Colab.
2.  Execute as células sequencialmente para carregar os dados, realizar as análises e gerar os gráficos.

O notebook é auto-executável e os dados são carregados diretamente de URLs, não sendo necessário baixar arquivos localmente.

## 📈 Análises e Resultados (Síntese)

*(Esta seção deve ser preenchida após a conclusão das análises no notebook. Aqui você pode adicionar uma breve síntese dos principais achados, como qual loja teve o menor faturamento, qual teve a pior avaliação, quais produtos se destacaram, etc. Você pode até adicionar algumas das visualizações mais importantes.)*

Com base na análise das métricas de faturamento total, faturamento mensal, vendas por categoria, avaliação média, produtos mais/menos vendidos e frete médio, foi possível identificar que a **[Nome da Loja com Menor Rendimento]** apresentou o menor desempenho geral.

*   [Mencione brevemente os principais motivos ou métricas que levaram a essa conclusão.]
*   [Opcional: Inclua uma imagem de um gráfico chave aqui, como o faturamento total por loja.]

A análise geográfica adicional revelou [descreva brevemente os padrões geográficos observados, por exemplo, se uma loja atende uma área menos populosa ou com menor poder aquisitivo].

## 🤝 Contribuição

Este projeto foi desenvolvido como parte do Challenge Alura Store. Contribuições são bem-vindas, sinta-se à vontade para propor melhorias ou novas análises.

## 📝 Licença

Este projeto está sob a licença MIT.

## Contato

[Seu Nome/Pseudônimo]
[Link para seu GitHub ou LinkedIn - Opcional]

# 📊 Desafio Alura Store

## 🎯 Objetivo

Este projeto tem como objetivo auxiliar o Senhor João, proprietário da rede fictícia Alura Store, na escolha sobre qual de suas quatro lojas deve ser vendida ou descontinuada para viabilizar um novo empreendimento. Para isso, realizamos uma análise de dados com base em informações de faturamento, desempenho de vendas, avaliações dos clientes, categorias e produtos mais vendidos, além do valor médio de frete.

--------------

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Python 3.8+
- pip ou conda (para instalação de pacotes)

### Instalação

1. Clone este repositório:
```
git clone https://github.com/Mateus-Redivo/AluraStore.git
cd AluraStore
```

2. Instale as dependências:
```
pip install -r requirements.txt
```

3. Execute os notebooks na ordem:
```
jupyter notebook notebooks/
```

--------------

## 📈 Visualizações e Insights

* **Faturamento por Loja:** Total vendido por cada estabelecimento
* **Vendas por Categoria:** Comparativo por tipo de produto entre as lojas
* **Média de Avaliações:** Satisfação dos clientes medida através das avaliações
* **Produtos Mais e Menos Vendidos:** Identificação dos itens populares e menos procurados
* **Frete Médio por Loja:** Análise do custo de entrega praticado por cada unidade

--------------

## 🔎 Ferramentas Utilizadas

🐍 Python

📓 Jupyter Notebook

--------------

## 📚 Bibliotecas

🐼 Pandas: Manipulação e análise de dados

📊 Matplotlib: Criação de visualizações e gráficos

📈 Seaborn: Visualizações estatísticas avançadas

🔢 Matplotlib.ticker: Formatação personalizada dos eixos

🧮 NumPy: Computação numérica

--------------

## 🧠 Conclusão 

Com base na análise dos dados apresentados, a recomendação é que o Senhor João venda a Loja 4. Essa decisão é sustentada pelos seguintes fatores:

* **Menor Faturamento:** A Loja 4 apresenta o menor faturamento entre todas (R$ 1.384.497,58), o que demonstra um desempenho financeiro abaixo das demais.

* **Menor Destaque em Produtos:** Embora o produto mais vendido da Loja 4 (cama box) esteja alinhado com as categorias populares (móveis), seu produto menos vendido (guitarra) pode indicar baixa aceitação de certos nichos. Isso evidencia um mix de produtos que pode não estar tão bem ajustado quanto nas outras lojas.

* **Avaliação Mediana:** A média de avaliação da Loja 4 (4.00) é ligeiramente superior à da Loja 1 (3.98), mas inferior à das Lojas 2 (4.04) e 3 (4.05). Isso sugere que a experiência do cliente, embora razoável, não se destaca.

* **Frete como Único Destaque:** O único ponto realmente forte da Loja 4 é o frete médio mais baixo (R$ 31.3). No entanto, esse diferencial isolado não compensa o baixo faturamento e o desempenho geral.

Dessa forma, vender a Loja 4 permitirá ao Senhor João capitalizar sobre o valor ainda existente nela e reinvestir esse recurso nas demais lojas, que apresentam melhor desempenho e maior potencial de crescimento. Ao focar nas Lojas 1, 2 e 3 — que têm melhores indicadores de faturamento, avaliações e alinhamento com as categorias mais vendidas — João poderá fortalecer sua operação, aumentar sua margem de lucro e melhorar a experiência do cliente nas lojas restantes.

## 🔗 Fonte dos Dados

Os dados utilizados nesta análise foram obtidos do repositório do challenge de data science da Alura:
* [Loja 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
* [Loja 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
* [Loja 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
* [Loja 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

## 👥 Contribuição

Para contribuir com este projeto:

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-analise`)
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova análise'`)
4. Faça push para a branch (`git push origin feature/nova-analise`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

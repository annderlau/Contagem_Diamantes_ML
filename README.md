# Atividade com o objetivo de desenvolver e treinar um algoritmo de regressão linear para prever o preço de um diamante.

---
**Professor:** José Eduardo Storopoli [link](https://github.com/storopoli)<p>
**Autores:** <br> Daniel Zanad [link](https://github.com/DanielZanad)
<br> Maicon Lidemi [link](https://github.com/annderlau)
<br> Matheus Siqueira Silva [link](https://github.com/slvsccp)
<br> Lucas Gomes [link](https://github.com/GFLucas8)
<br> Mônica Cristina Meireles [link](https://github.com/meireles89)
  
 **Data:** 11/10/2020

## Tecnologias utilizadas:
- **Google Colab**

## Sobre o Dataset Diamonds
O dataset diamonds foi baixado pelo Kaggle e pode ser encontrado neste [link](https://www.kaggle.com/shivam2503/diamonds). Está em formato de valores separados por vírgula (`.CSV`).

## Ele possui as seguintes variáveis:

- carat peso do diamante em quilates
- cut qualidade do corte do diamante
- color cor do diamante
- clarity uma medida de transparência do diamante
- depth profundidade total em pontos percentuais
- table largura do topo do diamante relativo ao seu ponto mais largo
- price: preço em dólares do diamante
- x comprimento em milímetros
- y largura em milímetros
- z profundidade em milímetros

## Etapas
1. Importar o dataset no pandas (`pd.read_csv`)
2. Calcular algumas estatísticas dos dados com pandas groupby
3. Fazer alguns gráficos dos dados com o matplotlib.pyplot
4. Preparar os dados para o Scikit-Learn
5. Treinar um modelo LinearRegression do Scikit-Learn para prever o price do diamante

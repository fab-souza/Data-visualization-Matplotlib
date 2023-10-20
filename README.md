# Data-visualization-Matplotlib
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/Data-visualization-Matplotlib)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Data Visualization: criação de gráficos com o Matplotlib**
| :label: Tecnologias | python
| :rocket: URL         | 
| :fire: Desafio     | Conteúdo do [curso](https://www.alura.com.br/curso-online-customizacao-matplot)

![](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/ae79c8d4-bb38-4c86-a56c-0e1f3f65244c)

# Sobre o curso 📚

Ainda no tópico *Visualização de Dados*, da formação [Data Science](https://www.alura.com.br/formacao-data-science), oferecido pela [Alura](https://www.alura.com.br/), passamos o foco para aprender a criar gráficos e visualizações de dados com a biblioteca [Matplotlib](https://matplotlib.org/). Desta vez, o curso foi ministrado pelo [Luis Meazzini](https://www.linkedin.com/in/lmeazzini/) e aprendi:

- conceitos sobre o funcionamento de figuras e eixos, 
- a personalizar as visualizações com diferentes cores, estilos e anotações, 
- e criar visualizações para diversos tipos de dados, como séries temporais e dados categóricos.

Em resumo, sair da configuração padrão:

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/aeba1e89-4b60-4cda-b6b9-85dca745ffd1)

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/ebc8d736-6f4f-49b0-9574-ef24e34dd4fa)

E desenvolver um gráfico que esteja mais alinhado com determinada situação/empresa:

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/84ccf88f-a1ad-4403-b01b-ef9bf5d772b5)

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/b33849cd-7d7e-4fac-a2ec-9b7bcf8db312)

# Minha prática 👩🏻‍💻

Para praticar o que aprendi, utilizei dois datasets, ambos disponíveis no [Kaggle](https://www.kaggle.com). O primeiro é sobre registros climáticos de mais de 40 regiões da [Austrália](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/) entre 2008 até 2017.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/c26350c4-6660-4cb4-9aad-9999a631dbb0)

O primeiro gráfico que decidi plotar foi referente às temperaturas máximas de Sydney, usando apenas o *.plot*, definindo as datas no eixo *x* e as temperaturas no eixo *y*:

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/81161c90-f880-4177-afab-774dc1d5abec)

Aos poucos, aumentei a figura, adicionei um título, uma legenda aos eixos, alterei seus tamanhos, coloquei uma legenda para a variável que está sendo apresentada e mudei a cor do gráfico.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/65b11db0-11f8-46af-9292-5c67ae663242)

Nada de muito diferente, certo? Até que o instrutor começou a apresentar configurações que eu não tinha explorado ainda, por exemplo, alterar a espessura da linha ou substituí-la por pontos ao longo do gráfico.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/1d0576bb-3d6c-4c2d-abc6-06e80aff14b6)
D![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/6841eac3-367a-43ed-85f9-ac157eaccadc)
![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/fb1a4b11-f347-48d1-aa9a-450a8aea2e17)

Até o momento, o gráfico mostra todos os registros, de 2008 até 2017. Porém, podemos limitar sua visualização, ao determinar um período, com o parâmetro *set_xlim*. Neste caso, determinei que o gráfico estivesse focado nos registros de 01/01/2016 até 01/01/2017.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/5491237f-3c10-4fe1-ae8f-6f1ba323b4c9)

Da mesma forma, também aprendi a criar um novo eixo e apresentar informações adicionais. Por exemplo, no gráfico “principal” temos os registros de 2016 e no gráfico menor, vemos todos os registros.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/db1a82e5-cf61-4d19-856f-b208031633d9)

Ou, podemos limitar os registros do gráfico principal com um mês, enquanto o segundo gráfico apresenta as informações do ano inteiro.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/7a5d06bc-a4fa-4baa-906c-97da9c1cfc78)

Uma outra configuração que achei interessante, foi apresentar linhas que indicam o maior e o menor valor dos dados, adicionando setas e texto apontando para estes pontos do gráfico.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/5fa01b46-e9cb-403a-9795-34c9e0deac4f)

---







# Conclusão 🏁





## Ferramentas utilizadas 🧰

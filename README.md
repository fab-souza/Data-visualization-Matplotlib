# Data-visualization-Matplotlib
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

![Badge code size](https://img.shields.io/github/languages/code-size/fab-souza/Data-visualization-Matplotlib)

| :placard: Vitrine.Dev |    |
| -------------  | --- |
| :sparkles: Nome        | **Data Visualization: criação de gráficos com o Matplotlib**
| :label: Tecnologias | python
| :rocket: URL         | Notebook no [Kaggle](https://www.kaggle.com/code/fabianadesouza/data-visualization-matplotlib)
| :fire: Desafio     | Conteúdo do [curso](https://www.alura.com.br/curso-online-customizacao-matplot)

![](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/ae79c8d4-bb38-4c86-a56c-0e1f3f65244c#vitrinedev)

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
![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/6841eac3-367a-43ed-85f9-ac157eaccadc)
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

O segundo dataset que utilizei foi referente ao [consumo de energia elétrica em uma indústria de aço](https://www.kaggle.com/datasets/csafrit2/steel-industry-energy-consumption/), com registros de janeiro de 2018 até dezembro de 2018. 

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/b7364299-2d33-4dd6-b15d-ed53064362c2)

Além das datas, este dataset tem uma coluna com os dias da semana. Então, plotei um gráfico apresentando a média de consumo de energia a cada dia da semana.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/2f2b8a7d-ab6b-4e4f-a4c2-294598cffb90)

Alterei seu tamanho, atribuí uma cor para cada dia, adicionei título, legendas e uma linha em volta das barras.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/72796df1-68f1-45f5-a5bf-7540fa56ff0e)

Ainda sobre a média de consumo de energia, desta vez, fiz um gráfico de pizza.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/38f607f0-8027-452b-baf9-b940e74fc1e5)

Mantive as cores que foram usadas no gráfico de barras, acrescentei a porcentagem de cada dia da semana e destaquei os dois dias em que o consumo é maior.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/c08c0030-1afc-4d2e-afa8-d88e49b83540)

No próximo passo, fiz um gráfico de dispersão entre o **consumo de energia** com a **potência reativa**.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/7d66d584-bb19-4a56-b2d6-eeff8b2c8963)

Este dataset também possui uma coluna chamada *Load_Type*, em que os registros são divididos em: *Carga Leve*, *Carga Média* e *Carga Máxima*. Utilizei esta informação para diferenciar os pontos no gráfico, mudando sua cor e forma.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/39cda042-9fe3-48ba-9b61-3590e0b4e07a)

Também aprendi a configurar gráficos do tipo *box-plot*, saindo da configuração padrão:

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/9110a67a-2c78-4b85-b226-df56564db856)

Até uma que tivesse tamanho e cores personalizadas.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/dea8e28b-1099-40be-b007-54dfd4ed89f1)

E finalizei com um histograma, saindo da configuração básica:

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/fcc69158-2556-4d47-92b6-db0b95996cb6)

Até desenvolver um histograma que apresentasse informações mais específicas.

![image](https://github.com/fab-souza/Data-visualization-Matplotlib/assets/67301805/d38f0a73-52ac-42f6-ba13-ab7c1fc4f356)

# Conclusão 🏁

Eu gostei bastante de fazer este curso, pois ele me mostrou que, dependendo da análise e seu conteúdo, o *matplotlib* consegue resolver muita coisa e apresentar os dados de formas mais assertivas e personalizadas.

---

## Ferramentas utilizadas 🧰

<p>
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
  <a href="https://numpy.org/" target="_blank" rel="noreferrer"> <img src="https://numpy.org/images/logo.svg" alt="numpy" width="40" height="40"/> </a>
  <a href="https://matplotlib.org/" target="_blank" rel="noreferrer"> <img src="https://matplotlib.org/_static/images/documentation.svg" alt="matplotlib" width="40" height="40"/> </a>
</p>

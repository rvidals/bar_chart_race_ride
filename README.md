# Corridad e gráfico de barras do crescimento populacional da RIDE e do Distrito Federal
Na apresentação em que o IBGE divulgou os dados preliminares do censo de 2022, foi mostrado um [gráfico](https://www.youtube.com/live/7ij6MwAqsl0?feature=share&t=9535) bem interessante que chagou atenção.
Esse gráfico mostrava de forma animada o crescimento populacional dos municípios mais populonos do Brasil desde 1872 até 2022, histórico dos censos realizados pelo
Instituto Brasileiro de Geografia e Estatistica (IBGE) até hoje.
Pesquisando um pouco, vi que esse tipo de gáfico tinha, não só um nome mas diversas soluções para a sua confecção. Esse tipo de apresentação
gráfica se chama Bar Chart Race ou em uma tradução livre: Corrida de Gráfico de Barras e possui algumas soluções em python para a sua criação. A que estou utilizando e que mais chamou a minha atençaõ é a bar-chart-race https://pypi.org/project/bar-chart-race/, devido a sua facilidade e funcionalidade.
É importante destacar que para essa biblioteca rode de forma redondinha, é necessário baixar duas ferramentas:

1) [ffmpeg](https://www.youtube.com/live/7ij6MwAqsl0?feature=share&t=9535): Para salvar o gráfico em MP4
2) [ImageMagick](https://imagemagick.org/): Para salvaar o gráfico em gif
Essas duas ferramentas foram instaladas usando o [Chocolatey](https://community.chocolatey.org/)

Portanto, após a solicitação da DEPAT, me debrucei sobre essa biblioteca e criamos um gráfico com a evolução do crescimento populacional da RIDE e DF ao longo dos anos,
isto é, desde 1960 até 2022. 

# Bibliotecas Utilizadas

- [Pandas](https://pandas.pydata.org/)
- [glob](https://docs.python.org/3/library/glob.html)
- [os](https://docs.python.org/3/library/os.html)
- [bar_chart_race](https://www.dexplo.org/bar_chart_race/)
  
# Autor
Rogerio Vidal de Siqueira
<a href="https://www.linkedin.com/in/rogerio-vidal-de-siqueira-9478aa136/" target="_blank" rel="noopener noreferrer">Meu Linkdin</a>

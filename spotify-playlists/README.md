# Overview
Esse trabalho é referente a disciplina Network Analysis. Ele aplica um estudo sobre a interação de artistas presentes em playlists no Spotify. Em 2018, o Spotify tornou público o Spotify Million Playlists. 

https://www.aicrowd.com/challenges/spotify-m

Esse dataset possui informações das playlists, como identificador de playlist, nome do autor, nome música, do artista, entre outros. 

Busquei gerar dados quantitativos sobre a Network gerada. O grafo é do tipo unDirected, ou seja não estamos considerando origem e destino das ligações dos Nodes. 

Weights foram considerados. Os weights representam a força da conexão entre os artistas. Quando em uma playlist tem um artista X e o artista Y, sendo que o artista Y aparece 2 vezes, ou seja, ele possui 2 músicas nessa playlist, então, o weight entre eles vai valer  3 (1 + 2). X e Y também irão ter um selfloop, o X vai ter um selfloop de 1 e o Y de 2.

Por fim, foi gerado usando o Gephi uma rede interativa. O deploy dela foi feito usando o Github Pages e pode ser acessado nesse link 

https://vilsonrodrigues.github.io/NetworkAnalysis/spotify-playlists/network

Os códigos base de análise foram fornecidos pelo professor da disciplina e pode ser encontrado em seu repositório no Github https://github.com/ivanovitchm 

# Reproducibility

Seguindo o .ipynb você consegue obter todos os arquivos que eu gerei. Por conveniência, eu subi os arquivos .pkl para que você consiga executar sem precisar rodar novamente as métricas custosas. Não dei upload no arquivo da network por causa do limite de tamanho imposto pelo próprio Github. Como excedeu muito ele não permitiu. Mas você pode rapidamente gerar ela e exportar seguindo os passos no notebook.

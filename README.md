# meu-spotify

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)

| :placard: Vitrine.Dev |     |
| -------------         | --- |
| :sparkles: Nome       | Analise do meu historico no spotify
| :label: Tecnologias   | Python, Pandas, matplotlib
| :rocket: URL          | https://github.com/wesleyfuchs/meu-spotify

<!-- Capa da Vitrine.dev-->
![spotify-capa](https://user-images.githubusercontent.com/55562529/227704719-d08cd9c8-f9ca-45e3-b321-134292144e2a.png#vitrinedev)

## Sobre o projeto 📚

Esse projeto é uma analise do meu historico do Spotify com o objetivo de descobrir as bandas e musicas que mais escutei ao decorrer dos anos </br>

Os dados foram obtidos atraves do site do [Spotify](https://www.spotify.com/br-pt/account/privacy/). Após solicitação recebi um arquivo json contendo as informações sobre meu historico de musicas ouvidas na plataforma, o arquivo contem:
- "endTime" : Data da ultima reprodução da musica
- "artistName" : Nome do artista
- "trackName" : Nome da musica
- "msPlayed" : total de milisegundos ouvidos

## Desenvolvimento

Após feito limpeza, tradução e alguns ajustes e correções dos dados foi possivel descobrir muitos fatos legais sobre meu histórico de musicas e apartir disso gerar graficos e tabelas como:</br>

![num_bandas](https://user-images.githubusercontent.com/55562529/227737214-a8ba1159-f863-44eb-8993-9d0db30b9c3a.png)</br>
![tempo_musicas](https://user-images.githubusercontent.com/55562529/227737640-1bad53af-a44d-4f2b-8e34-d1b2d0f4d33a.png)

### Bandas mais tocadas 

![bandas-minutos](https://user-images.githubusercontent.com/55562529/227737247-8d224a2d-6be5-4b66-82a8-d13c6b1114a0.png)

### Bandas com mais musicas diferentes que eu ouvi

![bandas-musicas](https://user-images.githubusercontent.com/55562529/227737345-2ba810de-0113-4b2a-a803-1c16a9e3c435.png)

### Musicas da banda que eu mais ouvi

![musicas_redhot](https://user-images.githubusercontent.com/55562529/227737717-959f640e-ef21-4ec3-8146-ba3f42c0dbe3.png)

### 10 musicas mais ouvidas

![musicas](https://user-images.githubusercontent.com/55562529/227737894-7114edab-3a74-4bdf-b5ad-e800090d7698.png)

As listas completas estão no [notebook](https://github.com/wesleyfuchs/meu-spotify/blob/main/Analise.ipynb) 


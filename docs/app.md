# Podcast Manager

### Descrição

- Um app ao estilo netflix, a onde eu possa centralizar diferentes episódios podcasts separados por categorias


### Domínio

- Podcasts feitos em vídeo

### Features

- Listar os episódios podcasts em sessões de categorias
    - [Saúde, bodybuilder, mentalidadde, humor]
- Filtrar episódios por nome de podcast

## Como

#### Feature:

Listar os episódios podcasts em sessões de categorias

### Como vou implementar:

Vou retornar em uma api rest(json), 
o nome do podcast, nome do episódio, imagem de capa, link, categorias 

```js
[
{
    podcastName: "flow",
    episode: "CBUM - Flow #319",
    videoId: "pQSuQmUfS30",
    cover: "https://i.ytimg.com/vi/pQSuQmUfS30/hq720.jpg",
    link: "https://www.youtube.com/watch?v=pQSuQmUfS30&pp=ygUJZmxvdyBjYnVt",
    categories: ["saúde", "esporte", "bodybuilder"]
},
{

    podcastName: "flow",
    episode: "FRANCIELLE MATTOS - Flow #308",
    videoId: "maBHQeVBXt4",
    cover: "https://i.ytimg.com/vi/maBHQeVBXt4/hq720.jpg",
    link: "https://www.youtube.com/watch?v=maBHQeVBXt4&list=PLWieWKZeFoVTAmITEhTfOpt-urqXw_pvS&index=13&ab_channel=FlowPodcast",
    categories: ["saúde", "esporte", "bodybuilder"]
};
]
```

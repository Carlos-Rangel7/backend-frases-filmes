# Frases de Filmes - Backend

Este é o backend de um projeto que gera **frases aleatórias de séries e filmes**.

A API retorna:
- Uma frase aleatória;
- O nome do **personagem** que disse a frase;
- O título da **série ou filme**;
- A **imagem de capa** da série/filme.

As informações são buscadas a partir de um banco de dados preenchido previamente com frases, personagens e imagens.

Exemplo de resposta da API:

```json
{
  "frase": "I'm not in danger, Skyler. I am the danger.",
  "personagem": "Walter White",
  "filme": "Breaking Bad",
  "poster": "https://link-para-imagem.jpg"
}
````

 ## Tecnologias do Back-End
 - Java 21
- Spring Boot
- PostgreSQL

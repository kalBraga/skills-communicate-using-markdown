# Aprendizado Diario

## Planejamento Matinal
- [ ] Confira o [blog do GitHub](https://github.blog/) para obter ideias de temas.
- [ ] Saiba mais sobre o [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Transforme minha primeira postagem de blog em uma página da web de fato.

## Revisão 
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```

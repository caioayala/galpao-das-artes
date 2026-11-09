# Galpão das Artes

Landing page da Galpão das Artes, marcenaria de móveis sob medida (desde 2003), que atende Umuarama (PR), Ponta Porã (MS) e região.

Instagram: [@moveisplanejados__xambre](https://www.instagram.com/moveisplanejados__xambre/)

## Estrutura

```
index.html   página inteira (HTML + CSS, sem JavaScript e sem build)
img/         fotos em WebP e o símbolo do logo
```

As fotos são quadros dos reels do Instagram, ampliados com [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) (modelo `realesrgan-x4plus`) e reduzidos para 1000 px de largura.

## Rodar localmente

Abra o `index.html` no navegador. Não há dependências.

## Deploy

Hospedado na Vercel, ligado a este repositório:

- push na `main` → deploy de produção
- pull request → deploy de preview com link próprio

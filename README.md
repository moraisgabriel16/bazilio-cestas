# Bazílio Cestas

Página de apresentação da Bazílio Cestas, com categorias de presentes, filtros e contato pelo WhatsApp.

HTML, CSS e JavaScript, sem dependências ou etapa de build.

## Executar

```sh
python -m http.server 5174 --directory dist
```

## Vercel

`vercel.json` configura `dist` como saída estática. Branch de produção: `main`.

## Conteúdo

- `dist/index.html`: estrutura e conteúdo.
- `dist/style.css`: estilo e layout responsivo.
- `dist/app.js`: filtros e mensagens de WhatsApp.
- `dist/assets/`: logotipo enviado pelo cliente e imagens ilustrativas.

A imagem da cesta de café da manhã foi gerada por IA. As demais fotos ilustrativas de alimentos são do Unsplash. Composição, disponibilidade, valores e condições de entrega são consultados diretamente com a empresa. Os botões abrem uma mensagem para o visitante revisar e enviar no WhatsApp.

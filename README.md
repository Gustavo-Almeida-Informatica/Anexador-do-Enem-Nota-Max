# ENEM Nota Max — Reel em Remotion

Projeto de Reel vertical animado para Instagram.

## Especificações
- 1080 × 1920 (9:16)
- 30 fps
- 15 segundos
- Cenas: contagem regressiva, datas das provas e chamada para o site
- Sem música incorporada: adicione uma faixa licenciada pela biblioteca do Instagram após publicar, ou use áudio próprio com direitos.

## Requisitos
- Node.js 18 ou superior
- npm

## Instalar e abrir a prévia
```bash
npm install
npm run start
```

Selecione a composição `EnemNotaMaxReel` no Remotion Studio.

## Renderizar MP4
```bash
npm run render
```

O vídeo será salvo em `out/enem-nota-max-reel.mp4`.

## Ajustes rápidos
- Textos e cores: `src/Reel.tsx`
- Duração, FPS e resolução: `src/Root.tsx`
- A arte de referência está em `public/referencia-enem-4-dias.png`.

## Observação
As datas 08/11 e 15/11 foram mantidas conforme a arte de referência fornecida. Confirme o calendário oficial antes de publicar.

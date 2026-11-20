# Sticker Player — MVP 01

Protótipo web instalável (PWA) para iPhone.

## Executar
Hospede os arquivos em um endereço HTTPS estático (por exemplo, GitHub Pages ou outro host estático). Abra `index.html` no Safari.

## Instalar no iPhone
Safari → Compartilhar → Adicionar à Tela de Início.

## Estado desta versão
- Importação de imagem local.
- Ajuste manual de posição, largura, altura e arredondamento.
- Prévia sobre fundos diferentes.
- Exportação PNG RGBA com transparência real fora da máscara.
- Nenhum upload para servidor.

## Limitação conhecida
A detecção automática inicial é uma estimativa baseada no formato típico e na posição do player, não uma segmentação inteligente treinada. É indispensável conferir e ajustar o contorno. Próxima etapa: implementar detecção geométrica mais robusta para prints reais de tela bloqueada do iOS 27, incluindo máscaras com cantos e transparências originais.

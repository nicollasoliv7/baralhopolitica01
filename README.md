# Vira a Carta: página de vendas

Página estática (um único `index.html`, sem build) do baralho para o 2º turno, edição esquerda.

## Antes de publicar

1. Em `index.html`, troque `CHECKOUT_URL` pelo link do seu checkout.
2. Substitua os espaços entre colchetes: vídeo de reação, razão social, CNPJ e e-mail de suporte.
4. A seção "É assim que a conversa pode virar" (`#exemplos`) usa prints **ilustrativos**, e a página diz isso. Quando tiver prints reais de clientes (com autorização), troque os arquivos em `img/depoimentos/`, borre nome, @ e foto, e só então mude o selo e o texto da seção para "depoimentos".
3. Troque o espaço tracejado "QR code da fonte" na carta de demonstração por um QR real da fonte, se quiser.

## Publicar

Qualquer hospedagem estática serve. Na Vercel: importe o repositório, sem framework e sem comando de build.

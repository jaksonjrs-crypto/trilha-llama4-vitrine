# Vitrine Autopilot 🚀

App que deixa afiliado no piloto automático.

## O que faz
- Avalia qualquer produto da Shopee com IA (modelo PyTorch portado para JS)
- Aceita formato brasileiro: 61,99 | 1.234,99
- Gera landing page pronta em HTML

## Como instalar no iPhone
1. Faça deploy no GitHub Pages (Settings > Pages)
2. Abra no Safari
3. Compartilhar > Adicionar à Tela de Início

## Resultado do modelo
Treinado com 8 produtos da Vitrine:
- Espremedor USB R$61,99 nota 4.8 -> 100% (AFILIA)
- Produto ruim R$199 nota 3.0 -> 0% (PULA)

## Stack
- React + Tailwind
- Lógica do modelo: Sigmoid((1-price_norm)*0.5 + (rating/5)*0.6 + sales_norm*0.5)
- 100% client-side, sem backend

@minhavitrinedosachados | Jakson Rodrigues
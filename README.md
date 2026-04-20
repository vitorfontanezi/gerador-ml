# Gerador de Anúncios ML — Lúmnia Iluminação

Ferramenta para geração rápida de anúncios em massa para o Mercado Livre.

## Como usar

1. Abra o `index.html` no navegador, ou acesse via GitHub Pages
2. Preencha os 4 passos: Dados → Fotos → Medidas → Gerar
3. Clique em **Copiar tudo (TSV)**
4. Cole na planilha do ML a partir da linha 5, célula A

## Funcionalidades

- Suporte a lâmpadas de **4,8W**, **6W (Stella)** e **7W**
- Título e descrição automáticos por potência, quantidade, cor e temperatura
- Fotos separadas por cor do spot (Preto / Branco / etc.)
- Quantidades pré-definidas + campo livre para qualquer quantidade
- Geração de até 25 linhas (limite do ML) por operação
- Descrição formatada com quebras de linha reais
- Geração de EAN-13 com dígito verificador válido
- 100% offline — não precisa de servidor ou internet

## Observação sobre EANs

Os EANs gerados são aleatórios (apenas o dígito verificador é matematicamente válido).
Substitua por EANs reais registrados em [gs1br.org](https://www.gs1br.org) antes de enviar ao ML.

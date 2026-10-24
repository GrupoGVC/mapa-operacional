# Mapa Operacional — Grupo GVC

Mapa logístico do Grupo GVC com clientes, unidades GVC, parceiros, fornecedores, destinadores, transportadores e recicladores.

**Acesse:** https://grupogvc.github.io/mapa-operacional/

## Como funciona

- O app é um único arquivo (`index.html`), sem instalação.
- Os dados ficam numa planilha do Google ("GVC Mapa Operacional — Banco de Dados", na conta comprasgrupogvc@gmail.com), acessada por um Apps Script publicado como App da Web ("GVC Mapa Operacional - API").
- Tudo que alguém cadastra, edita ou apaga é salvo na planilha automaticamente, e o mapa de todo mundo se atualiza sozinho a cada minuto.
- A URL do Apps Script já vem embutida no app (constante `DEFAULT_SHEETS_URL`), então ninguém precisa configurar nada.

## Atualizar o app

Substitua o `index.html` neste repositório. O GitHub Pages publica a nova versão em 1 ou 2 minutos.

## Atenção

O link é público: qualquer pessoa com ele consegue ver e editar os cadastros.

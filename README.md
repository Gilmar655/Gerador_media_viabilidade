# Dashboard — Viabilidade de Geradores MT

Base: Geradores_media_viabilidade(1).xlsx. Atualizada em 06/10/2026, às 08h54 (Brasília).
653 solicitações, 35 campos originais e 330 códigos de projeto após padronização de espaços.

## Publicar no GitHub Pages

1. Extraia todos os arquivos deste ZIP.
2. Envie index.html, style.css, app.js, data.js, a pasta assets, o Excel e .nojekyll para a raiz do repositório.
3. Nas configurações de Pages do repositório, selecione a branch que contém esses arquivos e a pasta raiz do repositório.
4. Aguarde a publicação e abra o endereço do GitHub Pages.

O ZIP já contém index.html na raiz. Preserve os nomes dos arquivos e a estrutura de assets. Não é necessária instalação nem compilação.

## Usar o painel

- Os filtros por regional, contratada, status, área, equipamento, técnico responsável, período e pesquisa atualizam os indicadores, gráficos e a tabela completa.
- Exportar Excel baixa a base inteira; Exportar seleção baixa todos os registros filtrados, independentemente da página visível.
- Importar Excel aceita o arquivo original ou uma exportação do painel com as 35 colunas. A importação vale para a sessão aberta e não atualiza automaticamente o repositório nem a base de outros usuários. Exporte para guardar sua seleção ou nova base.
- A aba Análise Contratadas original é uma referência estática. O comparativo principal e o comparativo exportado são recalculados a partir da base.
- O relógio usa o horário de Brasília. A data de atualização informa quando o arquivo-base foi carregado.
- Os 74 registros com alertas requerem conferência; os valores de origem foram preservados.

## Arquivos

- index.html: página principal.
- style.css: estilos responsivos e identidade visual.
- app.js: cálculos, filtros, tabela e importação/exportação.
- data.js: dados completos das duas abas.
- Geradores_media_viabilidade.xlsx: cópia fiel do novo Excel enviado, com nome compatível com o botão de download.
- assets/enel-brasil.png: logomarca Enel Brasil.
- assets/xlsx.full.min.js e assets/SheetJS-LICENSE.txt: leitura e exportação Excel local, sem dependência de CDN.
- .nojekyll: configura o serviço para servir diretamente os arquivos estáticos.

## Conferência da atualização

As duas abas foram examinadas. Os 653 IDs e os valores dos 35 campos são iguais aos da versão anterior; o cabeçalho da base agora está na primeira linha da aba Planilha2. A atualização preserva os dados e hiperlinks, ajusta as referências às linhas de origem, substitui o Excel de download e atualiza a data de carregamento.

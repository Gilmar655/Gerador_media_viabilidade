# Viabilidade de Geradores MT

Base: gerador_07_10_2026_(1).xlsx, fornecida em 07/10/2026.
679 solicitações, 35 campos originais e 340 códigos de projeto após padronização de espaços e caixa.
A planilha atual substitui integralmente a base publicada anteriormente. Nenhum registro anterior foi acrescentado.

## Usar o painel

- Filtros por regional, contratada, status, área, equipamento, técnico responsável, período e pesquisa atualizam indicadores, gráficos e planilha.
- Exportar Excel baixa a base inteira. Exportar seleção baixa todos os registros filtrados, independentemente da página visível.
- Excel original baixa a planilha fornecida nesta atualização, sem alterações.
- Importar Excel aceita as 35 colunas, inclusive quando o cabeçalho não está na primeira linha. A importação atualiza apenas a sessão aberta.
- Não há aba Análise Contratadas no arquivo fornecido hoje. O comparativo do painel é calculado a partir da base atual.
- O relógio e a data de carregamento usam o horário de Brasília.

## Publicação

Site estático servido pelo GitHub Pages na branch main, pasta raiz. Preserve os arquivos index.html, style.css, app.js, data.js, xlsx.full.min.js, enel-brasil.png e Geradores_media_viabilidade.xlsx na raiz. Não é necessária instalação nem compilação.

## Critérios

Cada linha é uma solicitação. Um projeto pode ter várias solicitações ou equipamentos. Aprovadas/concluídas = VIABILIDADE APROVADA + ORDEM CONCLUIDA. Casos decididos = aprovadas/concluídas + VIABILIDADE REPROVADA. Canceladas não entram na taxa de aprovação. Pendentes = agendadas + aguardando data + aguardando confirmação.

Prazo médio: dias de calendário entre solicitação e viabilidade, excluindo datas inválidas e intervalos negativos. Ganho médio: média simples de % GANHO entre 0 e 100%. CHI e CI não são somados, pois podem se repetir por projeto. Datas passadas de agendamento geram alertas para conferir o status e não comprovam falta de visita.

Valores, linhas, campos vazios e links da planilha original são preservados. A data de carregamento não equivale à data da última atividade. A biblioteca SheetJS mantém sua licença em SheetJS-LICENSE.txt.

## Conferência integral da planilha

Foram lidas todas as 2.998 linhas da área declarada, inclusive o cabeçalho, e todas as 35 colunas. A base contém 679 registros não vazios, 6 linhas vazias intercaladas e 2.312 linhas vazias após o último registro, na linha Excel 686. Os 679 IDs são distintos. Existem 3 células com erro #REF!: R620 (CI ORIGINAL), T620 (DM ORIGINAL) e J678 (NÚMERO DO EQUIPAMENTO). Esses erros são preservados e sinalizados no painel.

A seção Conferência das 35 colunas apresenta preenchimento, campos vazios, valores distintos, erros Excel, texto em campo numérico e datas inválidas para todos os registros filtrados. O cálculo considera a seleção inteira e não apenas a página visível.

# Viabilidade de Geradores MT

Base: Geradores_media_30_10_2026.xlsx, referência de 30/10/2026, publicada em 31/10/2026.
807 registros preenchidos, 35 campos originais e 400 códigos de projeto após padronização de espaços e caixa.
A planilha atual substitui integralmente a base anterior.

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

Foram conferidas todas as 3001 linhas e 35 colunas da área declarada. O cabeçalho está na linha 4. Há 807 registros preenchidos entre as linhas Excel 5 e 817, com 807 IDs distintos e 796 links. As 2190 linhas inteiramente vazias após o cabeçalho não contam como registros.

Erros de origem preservados: R623 (#REF!), T623 (#REF!), AC774 (#REF!). Os registros incompletos são mantidos e os campos ausentes aparecem na conferência.

A seção Conferência das 35 colunas analisa todos os registros filtrados, incluindo os que estão fora da página visível.

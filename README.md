# Projeto: App Web de Acompanhamento de Chamados

## Descrição
Este projeto é uma aplicação web interativa para acompanhamento, análise e visualização de chamados de TI, voltada ao Sistema de Gestão SAM e à conscientização SAM. O objetivo principal é facilitar o registro, acompanhamento e análise dos chamados realizados pelos usuários, com dashboards dinâmicos, filtros avançados e exportação de relatórios.

## Estrutura do Projeto
- **index.html**: Página principal da aplicação web, contendo toda a interface, lógica de navegação, filtros, gráficos e exportação.
- **libs/**: Pasta com bibliotecas e recursos utilizados no projeto.
    - **chart.umd.min.js**: Biblioteca Chart.js para geração de gráficos.
    - **fonts.css**: Estilos de fontes.
    - **xlsx.full.min.js**: Biblioteca SheetJS/xlsx para manipulação de arquivos Excel.

## Funcionalidades
- Upload de planilhas Excel (.xlsx, .xls, .csv, .ods) contendo chamados (guias "Requisição" e "Incidente").
- Navegação por abas: Dashboard, Analistas, Áreas, SLA, Tendências, Observações, Indicadores e Explorador.
- Filtros dinâmicos por data, analista, atendimento, software, centro de custo, diretoria e status.
- Visualização de KPIs e gráficos interativos (Chart.js):
    - Distribuição por status (Encerrado/Aberto)
    - Top 10 Softwares
    - Chamados por mês
    - Gargalos de SLA (críticos)
    - Chamados por analista, diretoria, centro de custo
    - Evolução e distribuição de SLA
    - Análise de observações por categoria
- Tabelas dinâmicas com busca, ordenação, paginação e drill-down por filtros.
- Exportação de relatórios completos para Excel (.xlsx) com KPIs, base filtrada, rankings e análise de observações.
- Interface responsiva, modo claro/escuro e navegação acessível.

## Como Executar
1. Certifique-se de que todos os arquivos estejam na mesma pasta.
2. Abra o arquivo `index.html` em um navegador web moderno (recomendado: Chrome, Edge, Firefox).
3. Carregue sua planilha Excel ou CSV conforme instruções na tela inicial.
4. Utilize os filtros, navegue pelas abas e exporte relatórios conforme necessário.

## Tecnologias Utilizadas
- **HTML5**
- **JavaScript** (toda lógica no client-side, sem backend)
- **CSS3**
- **Chart.js** (gráficos dinâmicos)
- **SheetJS/xlsx** (importação/exportação Excel)

## Observações
- O projeto é 100% client-side, não requer servidor ou backend.
- As bibliotecas estão incluídas localmente na pasta `libs`.
- Suporte a modo claro/escuro e navegação por teclado.

## Autoria
Desenvolvido para o acompanhamento de chamados do projeto SG SAM na Aché.

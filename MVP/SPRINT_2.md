# 📌 MVP - DoberLog (Sprint 2)

## 🎯 Objetivo do MVP

* **Qual problema resolve?** A dificuldade de gestores públicos em acessar, cruzar e analisar de forma rápida os dados complexos de comércio exterior (Comex Stat 2023-2026) dos municípios do Estado de São Paulo, o que atrasa o mapeamento analítico dos fluxos logísticos regionais e internacionais.
* **Qual hipótese será validada?** Se o uso do Google Colab (Python) para automatizar o tratamento de dados, combinado com a criação de um Dashboard interativo no Power BI, permite que gestores públicos identifiquem disparidades e potencialidades econômicas e logísticas regionais de forma mais rápida do que planilhas brutas tradicionais.
* **Qual valor será entregue ao usuário final?** Capacidade de cruzar dados de importação/exportação por município, gerando inteligência comercial e insights para a expansão econômica, logística e tecnológica do Estado.

---

## 📝 Descrição da Solução

Processamento de dados e a entrega visual desenvolvidos para esta etapa.

### Funcionalidades principais incluídas
* **Pipeline de Extração e Tratamento (Python/Colab):** Limpeza, estruturação e correlação dos dados brutos do Comex Stat (2023-2026) focados no Estado de São Paulo.
* **Dashboard Interativo (Power BI):** Telas iniciais mostrando índices agregados de exportação e importação das cidades paulistas.
* **Análise por Município:** Filtros interativos para comparar o desempenho comercial e fluxos logísticos entre diferentes cidades.

### Limitações conhecidas
* O volume massivo de dados de todos os municípios do estado pode gerar lentidão no processamento do Google Colab e no tempo de resposta inicial dos filtros do Power BI.
* Dados de transporte de cargas e modais específicos ainda podem conter lacunas ou generalizações devido à formatação de origem do Comex Stat.

### Escopo reduzido
* Foco estrito no fluxo comercial (Importação/Exportação) e indicadores econômicos das cidades do Estado de São Paulo no período de 2023 a 2026, adiando refinamentos complexos de cubagem de carga para as próximas etapas.

---

## 👥 Personas / Usuários-Alvo

### Gestor Público (Secretaria de Desenvolvimento Econômico / Logística)
* **Descrição:** Profissional responsável por planejar o crescimento regional, atrair investimentos e otimizar a infraestrutura de transporte do Estado.
* **Necessidades:** Identificar disparidades regionais, descobrir quais municípios estão em expansão tecnológica/econômica e entender o volume do fluxo internacional que passa por cada região.
* **Dores:** Perda de tempo limpando planilhas gigantescas e falta de clareza visual para comparar o desempenho logístico entre cidades vizinhas.

---

## 🔑 User Stories (Backlog do MVP - Sprint 2)

| ID | User Story | Prioridade | Estimativa |
| :--- | :--- | :--- | :--- |
| **US2** | Como gestor público, espero a extração, o tratamento e a estruturação dos dados de comércio exterior do Estado de São Paulo via Comex Stat (2023-2026)... | Alta | 3 horas |
| **US6** | Como gestor público, espero uma análise das cidades com indicadores favoráveis à expansão da economia e tecnológica nos próximos anos. | Alta | 2 horas |
| **US7** | Como gestor público, espero que utilizem os recursos do Google Colab para desenvolvimento e processamento dos dados na linguagem python 3+. | Média | 2 horas |
| **US8** | Como gestor público, espero a correlação dos dados extraídos do Comex Stat para comparação entre municípios... | Alta | 2 horas |
| **US10** | Como gestor público, espero a criação de um dashboard interativo mostrando índices de exportação e importação de cidades do estado de SP. | Alta | 3 horas |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais | Status |
| :--- | :--- | :--- |
| **01** | Estruturação do GitHub, Planejamento (5W2H) e Definição do Escopo. | Concluído |
| **02** | Script em Python (Colab) para tratamento de dados + Dashboard interativo no Power BI com índices de Importação/Exportação por Município. | **Em andamento** |

---

## 📊 Critérios de Aceitação

* O MVP deve permitir que o usuário filtre e compare os dados comerciais de pelo menos dois municípios paulistas simultaneamente no Power BI.
* O script em Python deve rodar no Google Colab sem erros de tipagem, gerando uma base limpa e unificada do período 2023-2026.
* **Métricas coletadas:** Tempo de execução do script de tratamento em Python; tempo de atualização dos gráficos do Power BI após a aplicação de filtros municipais.

---

## 📈 Métricas de Validação

* **Testes de Usabilidade:** Número de integrantes da equipe (ou validação externa) que testaram os filtros do dashboard e conseguiram extrair insights de disparidade comercial.
* **Feedback qualitativo:** Avaliação se a disposição dos gráficos de importação/exportação por cidade ficou intuitiva.
* **Indicadores técnicos:** Percentual de dados nulos ou corrompidos eliminados durante a etapa de tratamento no Python.

---

## 🚀 Próximos Passos

* Aprofundar a análise de transporte de cargas (identificar os itens mais transportados e tipos de veículos/modais mais utilizados - correspondente às US5, US9 e US11/12).
* Implementar a funcionalidade de exportação direta dos dados tratados para formatos amigáveis (CSV/Excel) diretamente pelo dashboard ou script final.
* Ajustes de usabilidade e design visual baseados nos feedbacks da Review da Sprint 2.

---

## 📂 Anexos / Evidências

* *[Link do repositório DoberLog no GitHub](https://github.com/Doberlog/API-1-Semestre-Logistica)*
* *Prints do código estruturado no Google Colab*
* *Screenshots das telas interativas do Dashboard no Power BI*

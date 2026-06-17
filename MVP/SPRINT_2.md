# 📌 MVP - DoberLog (Sprint 2)

## 🎯 Objetivo do MVP

* **Qual problema resolve?** A falta de cruzamento analítico de dados de transporte de cargas e a necessidade de correlacionar informações logísticas entre os diferentes municípios paulistas para identificar disparidades e potencialidades regionais.
* **Qual hipótese será validada?** Se o processamento via Python (Google Colab) permite correlacionar e mapear com precisão os itens mais transportados, auxiliando na identificação de municípios polo com indicadores favoráveis à expansão econômica e tecnológica.
* **Qual valor será entregue ao usuário final?** Uma análise preliminar dos fluxos logísticos de transporte de cargas e a identificação de disparidades regionais através do cruzamento automatizado de dados.

---

## 📝 Descrição da Solução

Processamento de dados focado em modais, veículos e correlações municipais desenvolvidos para esta etapa.

### Funcionalidades principais incluídas
* **Processamento de Dados de Carga (Python):** Estruturação e filtragem dos itens mais transportados na malha de comércio exterior paulista.
* **Análise de Correlação:** Algoritmos em Python (Colab) para comparar o fluxo comercial e identificar semelhanças ou disparidades logísticas entre os municípios.
* **Mapeamento de Tendências:** Indicadores que apontam quais cidades possuem infraestrutura ou dados favoráveis à expansão econômica e tecnológica nos próximos anos.

### Limitações conhecidas
* Nesta etapa, o foco ficou concentrado no processamento, tratamento e inteligência dos dados em Python, sem a consolidação total dos dashboards interativos de importação/exportação (que serão o foco visual da próxima Sprint).
* Algumas informações sobre tipos exatos de caminhões dependem do nível de detalhamento e preenchimento das bases do Comex Stat.

### Escopo reduzido
* Análise focada estritamente nas variáveis de transporte de cargas e correlações entre os municípios de São Paulo no período de 2023 a 2026.

---

## 👥 Personas / Usuários-Alvo

### Gestor Público (Secretaria de Desenvolvimento Econômico / Logística)
* **Descrição:** Profissional responsável por planejar o crescimento regional, atrair investimentos e otimizar a infraestrutura de transporte do Estado.
* **Necessidades:** Saber quais são as cidades polo em expansão e quais itens sobrecarregam mais os fluxos logísticos regionais.
* **Dores:** Dificuldade em cruzar dados de diferentes municípios de forma rápida para enxergar disparidades no comércio regional.

---

## 🔑 User Stories (Backlog do MVP - Sprint 2)

| ID | User Story | Prioridade | Estimativa |
| :--- | :--- | :--- | :--- |
| **US5** | Como gestor público, espero que me mostrem os dados de transporte de cargas; EX: quais são os itens mais transportados, qual o caminhão mais utilizado entre outros. | Baixa | - |
| **US6** | Como gestor público, espero uma análise das cidades com indicadores favoráveis à expansão da economia e tecnológica nos próximos anos. | Alta | - |
| **US7** | Como gestor público, espero que utilizem os recursos do Google Colab para desenvolvimento e processamento dos dados na linguagem python 3+. | Média | - |
| **US8** | Como gestor público, espero a correlação dos dados extraídos do Comex Stat para comparação entre municípios, permitindo a identificação de disparidades e potencialidades no fluxo comercial regional. | Alta | - |
| **US9** | Como gestor público espero que apresentem os dados de transporte de cargas para uma melhor visualização dos fluxos logísticos. | Alta | - |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais | Status |
| :--- | :--- | :--- |
| **01** | Exportação de dados (CSV/Excel), Extração e tratamento Comex Stat, Estruturação do GitHub e 5W2H (US1, US2, US3 e US4). | Concluído |
| **02** | Análise de transporte de cargas, correlação de dados entre municípios via Google Colab (Python 3+) e indicadores de expansão (US5, US6, US7, US8 e US9). | **Concluído** |

---

## 📊 Critérios de Aceitação

* O script em Python deve ser capaz de correlacionar e comparar os dados comerciais de diferentes municípios de São Paulo.
* Os resultados gerados devem destacar com clareza quais são as mercadorias/itens líderes em transporte nas regiões analisadas.
* **Métricas coletadas:** Tempo gasto para rodar o algoritmo de correlação no Google Colab e percentual de acerto na filtragem dos itens mais transportados.

---

## 📈 Métricas de Validação

* **Testes de Usabilidade:** Verificação interna se o script em Python unificou corretamente os dados logísticos por município sem gerar duplicidade.
* **Feedback qualitativo:** Avaliação da equipe se a análise de tendências de expansão das cidades gerou insights coerentes com a realidade do estado de SP.
* **Indicadores técnicos:** Execução com sucesso de 100% das funções de agrupamento de dados no ambiente do Google Colab.

---

## 🚀 Próximos Passos

* Desenvolvimento e entrega da Sprint 3, com foco total na criação das telas e gráficos visuais no Power BI (Dashboards interativos de exportação, importação e indicadores de desempenho da balança comercial - US10, US11 e US12).

---

## 📂 Anexos / Evidências

* *[Link do repositório DoberLog no GitHub](https://github.com/Doberlog/API-1-Semestre-Logistica)*
* *Insira aqui prints das linhas de código de correlação geradas no Google Colab*
* *Insira aqui os resultados em tabelas ou gráficos gerados a partir do script em Python*

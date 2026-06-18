# 📌 MVP - DoberLog (Sprint 3)

## 🎯 Objetivo do MVP

* **Qual problema resolve?** A falta de uma interface amigável, centralizada e interativa que permita aos gestores públicos visualizarem os índices comerciais e monitorarem o desempenho da balança comercial dos municípios de São Paulo sem depender de códigos ou planilhas brutas.
* **Qual hipótese será validada?** Se a consolidação dos dados tratados em um dashboard interativo no Power BI, com páginas específicas para importação, exportação e balança comercial, reduz o tempo de análise estratégica e apoia o monitoramento regional.
* **Qual valor será entregue ao usuário final?** Um painel gerencial interativo completo que unifica o desempenho importador e exportador, entregando o saldo da balança comercial dos municípios paulistas de forma visual e intuitiva.

---

## 📝 Descrição da Solução

Etapa final de integração visual dos dados e entrega do ecossistema do Dashboard no Power BI.

### Funcionalidades principais incluídas
* **Dashboard Interativo (Power BI):** Construção da interface visual contendo gráficos, cartões e filtros interativos de exportação e importação.
* **Visão de Importação por Município:** Painel dedicado especificamente para monitorar o fluxo de entrada de mercadorias no nível municipal.
* **Indicadores de Desempenho da Balança Comercial:** Cálculo e exibição visual do saldo comercial regional (Exportações vs. Importações) para monitoramento do desempenho econômico.

### Limitações conhecidas
* O carregamento inicial dos gráficos por cidade pode apresentar uma leve latência devido ao volume histórico consolidado (2023-2026) que alimenta o Power BI.
* A precisão na segmentação por bairros ou sub-regiões não é possível, limitando-se ao escopo municipal fornecido pelo Comex Stat.

### Escopo reduzido
* Foco total nas métricas gerenciais e na interatividade do dashboard (filtros por cidades e anos), concluindo a entrega de todas as análises planejadas no backlog do produto.

---

## 👥 Personas / Usuários-Alvo

### Gestor Público (Secretaria de Desenvolvimento Econômico / Logística)
* **Descrição:** Profissional responsável por planejar o crescimento regional, atrair investimentos e otimizar a infraestrutura de transporte do Estado.
* **Necessidades:** Avaliar quais municípios registram superávit ou déficit comercial e apresentar relatórios claros sobre o fluxo de importação e exportação regional para o alto escalão governamental.
* **Dores:** Dificuldade em gerar relatórios visuais rápidos e consolidados que mostrem o panorama geral da balança comercial do estado.

---

## 🔑 User Stories (Backlog do MVP - Sprint 3)

| ID | User Story | Prioridade | Estimativa |
| :--- | :--- | :--- | :--- |
| **US10** | Como gestor público, espero a criação de um dashboard interativo mostrando índices de exportação e importação de cidades do estado de São Paulo. | Alta | - |
| **US11** | Como gestor público espero que no dashboard tenha os dados de importação dos municípios do estado de São Paulo. | Alta | - |
| **US12** | Como gestor público, espero que o dashboard apresente os indicadores de desempenho exportador dos municípios do Estado de São Paulo, visando ao monitoramento da balança comercial regional. | Alta | - |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais | Status |
| :--- | :--- | :--- |
| **01** | Exportação de dados (CSV/Excel), Extração e tratamento Comex Stat, Estruturação do GitHub e 5W2H (US1, US2, US3 e US4). | Concluído |
| **02** | Análise de transporte de cargas, correlação de dados entre municípios via Google Colab (Python 3+) e indicadores de expansão (US5, US6, US7, US8 e US9). | Concluído |
| **03** | Desenvolvimento do Dashboard interativo no Power BI com painéis de importação, exportação e indicadores de desempenho da balança comercial regional (US10, US11 e US12). | **Concluído** |

---

## 📊 Critérios de Aceitação

* O Power BI deve exibir corretamente as abas ou filtros para alternar entre as visões de exportação, importação e balança comercial municipal.
* Ao selecionar um município do Estado de São Paulo, todos os cartões e gráficos do painel devem filtrar os índices automaticamente em tempo real.
* **Métricas coletadas:** Tempo de resposta na atualização dos gráficos ao aplicar filtros por município e total de registros financeiros validados no painel.

---

## 📈 Métricas de Validação

* **Testes de Usabilidade:** Simulação de uso onde os integrantes da equipe testaram a navegação entre os indicadores de importação e balança comercial no dashboard.
* **Feedback qualitativo:** Confirmação se os gráficos gerados no Power BI facilitam o monitoramento da balança comercial das cidades polo mapeadas.
* **Indicadores técnicos:** Correspondência exata (100% de match) entre os valores financeiros gerados no dashboard e a base tratada em Python na Sprint anterior.

---

## 🚀 Próximos Passos

* Preparação final para a **Feira de Soluções**, focando na gravação do vídeo demonstrativo da aplicação (MVP) e consolidação da documentação final do repositório no GitHub.

---

## 📂 Anexos / Evidências

* *[Link do repositório DoberLog no GitHub](https://github.com/Doberlog/API-1-Semestre-Logistica)*
* **Tela de Exportação e Importação por Cidade:**
  ![Páginas do Power BI](LINK_OU_ARRANQUE_O_PRINT_AQUI)
* **Painel Geral com o Saldo Final da Balança Comercial:**
  ![Saldo da Balança Comercial](LINK_OU_ARRANQUE_O_PRINT_AQUI)

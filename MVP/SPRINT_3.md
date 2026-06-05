# 📌 MVP - DoberLog (Sprint 3)

## 🎯 Objetivo do MVP

* **Qual problema resolve?** A falta de visibilidade detalhada sobre os fluxos físicos de transporte de cargas (modais, veículos mais utilizados e tipos de mercadorias mais movimentadas) e a necessidade de monitorar indicadores específicos de importação e balança comercial para os municípios do Estado de São Paulo.
* **Qual hipótese será validada?** Se a inclusão de dados operacionais de transporte (como o perfil de veículos e mercadorias predominantes) unida a visões específicas de importação no Power BI permite que o gestor identifique gargalos de infraestrutura e assimetrias na balança comercial regional de forma preditiva.
* **Qual valor será entregue ao usuário final?** Um mapeamento logístico e comercial completo, permitindo ao gestor público entender não apenas *quanto* a cidade negocia economicamente, mas *como* essa carga se movimenta fisicamente e quais são as demandas de infraestrutura de transporte.

---

## 📝 Descrição da Solução

Evolução do dashboard e do processamento de dados com foco em inteligência logística e balança comercial.

### Funcionalidades principais incluídas
* **Painel Logístico de Cargas:** Gráficos detalhando os itens mais transportados e estimativas/perfis de transporte (tipos de caminhões/modais mais comuns aplicados ao fluxo do estado).
* **Visão Dedicada de Importação:** Telas exclusivas no Power BI focadas na entrada de insumos e mercadorias nos municípios paulistas.
* **Indicadores da Balança Comercial:** Visualização de desempenho exportador/importador e saldo comercial consolidado das regiões.

### Limitações conhecidas
* A consolidação de dados de modais específicos (rodoviário, ferroviário, aéreo) depende estritamente do nível de detalhamento disponível nas atualizações recentes do Comex Stat para o período de 2023-2026.
* Maior consumo de memória no Power BI devido ao cruzamento de dados de peso (KG) e valor (FOB) com variáveis de transporte.

### Escopo reduzido
* Consolidação das regras de negócio logísticas (foco nos principais produtos e fluxos agregados), deixando para a sprint final apenas as funções de exportação automatizada de relatórios externos (CSV/Excel).

---

## 👥 Personas / Usuários-Alvo

### Gestor Público (Secretaria de Desenvolvimento Econômico / Logística)
* **Descrição:** Profissional responsável por planejar o crescimento regional, atrair investimentos e otimizar a infraestrutura de transporte do Estado.
* **Necessidades:** Compreender quais rodovias e rotas sofrem maior pressão de carga com base nos itens mais transportados e monitorar se os municípios mantêm uma balança comercial superavitária.
* **Dores:** Dificuldade em cruzar o valor financeiro da mercadoria com o impacto físico (peso e cubagem presumida) que ela gera na malha de transportes local.

---

## 🔑 User Stories (Backlog do MVP - Sprint 3)

| ID | User Story | Prioridade | Estimativa |
| :--- | :--- | :--- | :--- |
| **US5** | Como gestor público, espero que me mostrem os dados de transporte de cargas; EX: quais são os itens mais transportados, qual o caminhão mais utilizado entre outros. | Alta | 2 horas |
| **US9** | Como gestor público espero que apresentem os dados de transporte de cargas para uma melhor visualização dos fluxos logísticos. | Alta | 2 horas |
| **US11** | Como gestor público espero que no dashboard tenha os dados de importação dos municípios do estado de São Paulo. | Alta | 3 horas |
| **US12** | Como gestor público, espero que o dashboard apresente os indicadores de desempenho exportador dos municípios do Estado de São Paulo, visando ao monitoramento da balança comercial regional. | Alta | 3 horas |

---

## 📅 Sprint(s) Relacionadas

| Sprint | Entregas Principais | Status |
| :--- | :--- | :--- |
| **01** | Estruturação do GitHub, Planejamento (5W2H) e Definição do Escopo. | Concluído |
| **02** | Script em Python (Colab) para tratamento de dados + Dashboard interativo no Power BI com índices de Importação/Exportação por Município. | Concluído |
| **03** | Painel de transporte de cargas (itens e perfis de veículos), visão isolada de importação e indicadores da Balança Comercial regional no Power BI. | **Em andamento** |

---

## 📊 Critérios de Aceitação

* O Dashboard deve possuir uma aba ou seção dedicada exclusivamente à análise do transporte de cargas (mostrando os produtos líderes em movimentação).
* O sistema deve exibir claramente o saldo da balança comercial (Exportações (-) Importações) ao selecionar um município ou região do estado de SP.
* **Métricas coletadas:** Tempo de resposta na transição entre as páginas de importação e exportação; consistência dos valores de peso líquido agregados por tipo de produto.

---

## 📈 Métricas de Validação

* **Testes de Usabilidade:** Validação da navegação entre as novas páginas do relatório de importação e transporte.
* **Feedback qualitativo:** Avaliação se os dados de transporte (itens mais transportados) trazem insights claros para a tomada de decisão em logística pública.
* **Indicadores técnicos:** Verificação da integridade das correlações feitas no Python para garantir que os dados logísticos batam com os totais financeiros informados na Sprint 2.

---

## 🚀 Próximos Passos

* Implementação da User Story final (**US1**): Criar a funcionalidade que permite ao gestor exportar os dados limpos, tratados e correlacionados diretamente para arquivos CSV ou Excel.
* Refinamento estético final do Dashboard do Power BI (UX/UI) e documentação completa da arquitetura do projeto no repositório.

---

## 📂 Anexos / Evidências

* *[Link do repositório DoberLog no GitHub](SEU_LINK_AQUI)*
* *Insira aqui os prints das novas tabelas de transporte tratadas no Python*
* *Insira aqui os screenshots das novas telas do Dashboard (Balança Comercial e Importações) no Power BI*

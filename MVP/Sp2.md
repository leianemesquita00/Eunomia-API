# 📌 MVP 
## Mapeamento do Ecossistema Industrial e de Serviços da Região de São José dos Campos.   

## 🎯 Objetivo do MVP

- Consolidar a camada de inteligência analítica e espacial do ecossistema, permitindo a triagem de dados por CNAE e natureza jurídica, visualize a dispersão geográfica no município e avalie o impacto no mercado de trabalho.

---

## 📝 Descrição da Solução  
- Visualização Geoespacial Interativa: Um mapa de calor dinâmico da região de São José dos Campos que exibe com precisão a distribuição geográfica dos principais setores e polos econômicos, facilitando a identificação visual de aglomerações produtivas.

- Filtros Avançados por Classificação Econômica (CNAE): Painéis de segmentação baseados nas subclasses do IBGE, possibilitando isolar subsetores específicos, ramos de atividade ou processos produtivos detalhados de cada estabelecimento.

- Análise de Perfil Jurídico e Estrutural: Módulos de consulta para identificar a natureza jurídica predominante na cidade, permitindo compreender o perfil societário e a tipologia dos estabelecimentos locais.

- Dimensão do Mercado de Trabalho e Vínculos Empregatícios: Indicadores comparativos que avaliam o tamanho dos estabelecimentos e a quantidade de vínculos ativos (com distinção de vínculos CLT ou PJ), medindo o impacto e a influência de cada atividade no mercado de trabalho joseense. 

---

## 👥 Personas / Usuários-Alvo 
- **Analista de dados:** Funcionário que busca certas informações a fim de interpretá-las e obter insights acerca da cidade de São José dos Campos, Visualizar os principais setores e classes economicas da cidade e Dificuldade de interpratação dos dados a partir do banco de dados incial por falta de clareza e identificação de informaçoes lá contidas  

---

## 🔑 User Stories (Backlog do MVP)

| Rank | Prioridade | User Story | Sprint |                                                    
|-----|----------|------------------------------------------------------------------------|------------|
| 3 | Alta |Como analista, quero saber como estes setores estão distribuídos geograficamente para compreender a concentração das atividades econômicas na região.  | 2|
| 4 | Alta | Como analista, quero consultar os dados dos setores utilizando critérios de seleção variados, como os principais processos realizados, identificados pela subclasse CNAE do IBGE, para filtrar e contemplar apenas sobre informações específicas de cada empresa.  | 2 |
| 5 | Alta | Como analista, quero identificar a natureza jurídica dos estabelecimentos para entender quais tipos predominam uma cidade e realizar escolhas que contemplam essa distribuição. | 2 |
| 8 | Média | Como analista, quero comparar os diferentes estabelecimentos por seu tamanho e quantidade de vínculos ativos, CLT ou não, para compreender a influência no mercado de trabalho joseense de cada um destes. | 2 |
| 13 | Baixa | Como analista, quero consultar a metodologia utilizada nas análises e organização, para compreender a obtenção e compilação dos resultados obtidos. | 2 |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     |Coleta, tratamento inicial via Google Colab (Python) e estruturação das primeiras visualizações no Power BI | Concluído|
| 02     | Refinamento dos dashboards, validação com o cliente (CADI/Secretaria) e consolidação da documentação no GitHub |  Concluído |

---

## 📊 Critérios de Aceitação 
- Além da conectividade entre os campos, deve ser comprovada que é possível a filtragem de dados sem perda de informações
- Visualização de dados relevantes através de montagens gráficas inciais
- Métricas coletadas: Respostas consistentes e sem perda de dados.

---

## 📈 Métricas de Validação   
- Desempenho e Interatividade: Tempo de carregamento do mapa de calor e aplicação de filtros em menos de 3 segundos.
- Cobertura de Dados: 100% dos registros essenciais da região de São José dos Campos tratados,representados corretamente nas visualizações do Power BI.
- Aderência aos Requisitos: Validação de que todas as user story de usuário planejadas para a Sprint 2 entregam os resultados analíticos esperados pelo analista/usuário-alvo.  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback;

- Ajustes de usabilidade: Otimização do layout visual e paleta de cores do Power BI, consulta com o cliente a fim de identificar quais informações e respostas este considera mais desejáveis/importantes para seus fins e desenvolvimento mais detalhado e formalizado da documentação necessária.

---

## 📂 Anexos / Evidências

- Link [PowerBI](https://app.powerbi.com/view?r=eyJrIjoiYmQ0NDQ4YzYtNjc2Ni00N2FmLTlhMzUtZGY3MWY3NTBhNjdmIiwidCI6ImVhYmU2NGM1LTY4ZjUtNGE3Ni04MzAxLTk1NzdhNjc5ZTQ0OSIsImMiOjR9)


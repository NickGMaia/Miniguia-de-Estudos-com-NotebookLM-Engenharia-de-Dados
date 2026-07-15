# 📘 Miniguia de Estudos com NotebookLM — Engenharia de Dados

> Projeto desenvolvido para o Desafio de Projeto da DIO, explorando o uso de Inteligência Artificial (NotebookLM) como ferramenta de aprendizagem ativa sobre Engenharia de Dados.

---

## 🎯 Contexto e Objetivos

**Assunto escolhido:** Engenharia de Dados

**Por que escolhi esse tema:** Este é o tema central do curso que estou realizando na DIO, o Bootcamp Bradesco - GenAI, Dados & Cyber, e também dialoga diretamente com uma formação anterior que concluí, o bootcamp TOTVS - Fundamentos de Engenharia de Dados e Machine Learning. Criar esse caderno temático é uma forma de consolidar e aprofundar esse conhecimento.

**Objetivos de estudo:**
- Melhorar meu conhecimento geral sobre a área de Engenharia de Dados
- Entender os fundamentos e o ciclo de vida completo da engenharia de dados (não apenas ferramentas isoladas)
- Traçar um plano de próximos passos de estudo com base nos cursos e certificações que já possuo
- Aplicar esse conhecimento na prática, avaliando criticamente um projeto real (ETL) que já desenvolvi

---

## 📚 Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM:

1. **Fundamentos de Engenharia de Dados: Projete e Construa Sistemas de Dados Robustos** — Joe Reis e Matt Housley (livro) — obra de referência que define os princípios e o ciclo de vida da engenharia de dados, com foco em fundamentos agnósticos de ferramenta
2. **Vídeo do YouTube 1** — https://www.youtube.com/watch?v=UmSNTnBP7nY
3. **Vídeo do YouTube 2** — https://www.youtube.com/watch?v=mPSzL8Lurs0
4. **Vídeo do YouTube 3** — https://www.youtube.com/watch?v=VdGVmqiJkeg

> Critério de seleção: combinei uma fonte teórica de referência (o livro de Reis e Housley, amplamente reconhecido na área) com conteúdos em vídeo que trazem discussões e visões práticas complementares sobre engenharia de dados.

---

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Prompt 1 — Primeiros passos na área

- **Pergunta feita:** "Quais são os primeiros passos para começar na área de dados?"
- **Resposta obtida (resumo):** O NotebookLM organizou a resposta em 6 pilares: (1) focar nos fundamentos e no ciclo de vida da engenharia de dados em vez de ferramentas isoladas; (2) desenvolver engenharia de software rigorosa (SQL, Python, JVM, bash); (3) entender as ferramentas a fundo para evitar custos e ineficiências; (4) desenvolver pensamento sistêmico (systems thinking); (5) adotar mentalidade de negócio e comunicação; (6) manter autoestudo contínuo e usar IA com responsabilidade, sem que ela vire uma "muleta" que mascara a falta de conhecimento de arquitetura.
- **Fontes citadas pela IA:** o livro de Joe Reis e Matt Housley foi a base principal, com referências numeradas ao longo da resposta.
- **Observação/dificuldade:** a resposta veio bem estruturada de primeira, mas era genérica — não conectava com a minha situação real (cursos que já fiz).
- **Ajuste feito:** ao invés de perguntas isoladas, decidi enviar meu histórico de cursos/certificações na sequência, pedindo que a IA cruzasse essa informação com o conteúdo das fontes.

### Prompt 2 — Próximo passo com base no currículo

- **Pergunta feita:** "Qual o próximo passo para quem tem esses cursos/certificações" (seguido da lista completa de cursos e certificações já concluídos: bootcamp TOTVS/DIO, cursos de Python, Git/GitHub, banco de dados relacionais e ETL, Excel/Copilot, cloud computing, Machine Learning, cursos de Alura em Python OO, Flask, JavaScript, SQLite, e certificação de inglês)
- **Resposta obtida (resumo):** a IA reconheceu a base técnica já construída (Python, Flask, JavaScript, SQL, Git/GitHub, noções de nuvem e ETL) e apontou 7 próximos passos concretos: aprofundar engenharia de software rigorosa (testes automatizados, debugging); praticar o ciclo de vida completo da engenharia de dados ponta a ponta (geração, armazenamento, ingestão, transformação, serviço); dominar orquestração de dados (Airflow, Dagster, Prefect); estudar modelagem de dados analítica (esquema estrela, Inmon, Data Vault); ganhar experiência prática em nuvem (AWS, GCP, Azure) com atenção a custos (FinOps); aprender DataOps e observabilidade; e desenvolver pensamento sistêmico.
- **Fontes citadas pela IA:** novamente ancorada no livro de Reis e Housley, com referências numeradas específicas para cada recomendação.
- **Observação/dificuldade:** essa foi a melhor resposta obtida — bem mais útil e personalizada do que perguntas genéricas, porque forneci contexto detalhado (meu histórico real) em vez de só perguntar em abstrato.
- **Lição:** fornecer contexto específico (currículo, projeto, situação real) no prompt gera respostas muito mais acionáveis do que perguntas genéricas sobre o tema.

### Prompt 3 — Avaliação crítica de um projeto real

- **Pergunta feita:** "Irei te encaminhar a documentação de um ETL meu, e quero me diga como melhorar para próximos projetos com base no que me disse" (seguido do README completo do meu projeto real de ETL de gestão de estoque: https://github.com/NickGMaia/ETL_gest-o_estoque)
- **Resposta obtida (resumo):** a IA elogiou a cobertura completa do fluxo ETL (extração, transformação, carga) e o foco em valor de negócio real, mas apontou 5 pontos de evolução, todos ancorados nos fundamentos discutidos anteriormente: (1) desacoplar o pipeline em etapas independentes (ingestão, armazenamento, transformação, serviço); (2) abandonar o CSV local em favor de armazenamento em nuvem (S3/GCS) e formatos colunares como Parquet; (3) substituir a execução manual por um orquestrador real (Airflow, Dagster, Prefect) em vez de scripts rodados via cron; (4) implementar testes de qualidade e observabilidade de dados (DataOps); (5) evoluir o serviço de dados de um PPTX estático para um Data Warehouse conectado a ferramentas de BI (Power BI, Metabase, Superset).
- **Fontes citadas pela IA:** a resposta amarrou cada recomendação de volta aos conceitos do livro, mostrando como aplicar a teoria em um projeto concreto.
- **Dificuldade encontrada:** nenhuma relevante — o prompt funcionou bem de primeira porque já vinha de um histórico de conversa consistente (perguntas anteriores construíram contexto).
- **Lição:** usar o NotebookLM em sequência, construindo contexto ao longo da conversa, e trazer artefatos reais (como um README de projeto) para avaliação é uma forma poderosa de transformar teoria em feedback prático e aplicável.

> 💡 **Lição geral aprendida:** as melhores respostas não vieram de perguntas genéricas sobre o tema, e sim de perguntas que traziam contexto pessoal concreto — meu currículo, meu projeto real. Isso confirma um dos próprios princípios discutidos nas fontes: usar IA como assistente de análise crítica, não como substituto do raciocínio.

---

## 🗂️ Miniguia de Estudo (Entrega Final)

### Resumo estruturado

**O que é Engenharia de Dados**
Área focada em construir sistemas de dados robustos, ancorada em princípios e paradigmas que não mudam com o tempo — em vez de estar atrelada a ferramentas específicas (Spark, Snowflake etc.) que vêm e vão. O ponto central é o ciclo de vida da engenharia de dados: geração (nos sistemas de origem), armazenamento, ingestão, transformação e serviço dos dados para os consumidores finais.

**Engenharia de software como base**
Profissionais de dados precisam aplicar rigor de engenharia de software: código de qualidade, performático, testável e depurável. As linguagens centrais da área são SQL, Python, linguagens JVM (Java/Scala) e linha de comando (bash).

**Pensamento sistêmico e foco em negócio**
Mais do que executar tarefas isoladas, o engenheiro de dados precisa enxergar o pipeline de ponta a ponta, entender onde estão os gargalos, e sempre conectar o trabalho técnico a um valor real de negócio — comunicando-se bem com áreas técnicas e não técnicas.

**Orquestração e DataOps**
Pipelines reais têm múltiplas dependências e precisam de coordenação automatizada e monitorada — é o papel de orquestradores como Apache Airflow, Dagster e Prefect. Junto a isso, práticas de DataOps (inspiradas no DevOps) trazem testes automatizados, monitoramento e resposta a incidentes, evitando que dados ruins cheguem "silenciosamente" aos usuários finais.

**Modelagem e armazenamento moderno**
Bancos analíticos (OLAP/Data Warehouses) exigem modelagens diferentes das tradicionais (OLTP) — como esquema estrela (Kimball), modelo de Inmon e Data Vault. Formatos como CSV são frágeis para engenharia de dados; formatos colunares como Parquet, armazenados em soluções de objeto na nuvem (S3, GCS), são preferíveis por preservarem schema e performance.

**Da entrega estática ao self-service analytics**
Relatórios estáticos (como PPTX) têm seu valor, mas o mercado moderno caminha para Data Warehouses conectados a ferramentas de BI (Power BI, Metabase, Looker Studio, Superset), permitindo que os próprios usuários explorem os dados.

### Glossário

| Termo | Definição |
|---|---|
| Ciclo de vida da engenharia de dados | Fluxo que mapeia geração, armazenamento, ingestão, transformação e serviço dos dados |
| ETL | Extract, Transform, Load — processo de extrair dados da origem, transformá-los e carregá-los no destino final |
| Orquestração | Coordenação automatizada e monitorada de múltiplos jobs de dados, geralmente organizados como um DAG (Grafo Acíclico Dirigido) |
| DataOps | Aplicação de práticas de DevOps (integração contínua, testes, automação, monitoramento) ao ambiente de dados |
| OLTP | Online Transaction Processing — bancos otimizados para transações do dia a dia (ex: sistemas de vendas) |
| OLAP | Online Analytical Processing — bancos otimizados para análise, típicos de Data Warehouses |
| Data Warehouse | Armazém de dados estruturado para consultas analíticas, geralmente alimentando ferramentas de BI |
| Parquet | Formato de arquivo colunar, eficiente e que preserva schema, usado como alternativa moderna ao CSV |
| FinOps | Prática de gestão de custos em ambientes de nuvem |
| Pensamento sistêmico (Systems Thinking) | Capacidade de enxergar o fluxo de dados de forma holística, identificando gargalos e trade-offs de arquitetura |
| Observabilidade de dados | Monitoramento contínuo da saúde e qualidade dos dados ao longo do pipeline |
| Acoplamento (baixo) | Princípio de design onde componentes do sistema são independentes entre si, facilitando manutenção e evolução |

### Prompts reutilizáveis para revisão futura

- `"Explique [conceito de engenharia de dados] como se eu tivesse 12 anos, usando uma analogia."`
- `"Com base no que já discutimos sobre engenharia de dados, quais seriam os próximos 3 passos de estudo para alguém com [minha experiência/cursos]?"`
- `"Aqui está a documentação de um projeto meu: [colar README/código]. Com base nos fundamentos de engenharia de dados que já vimos, como posso melhorar esse projeto?"`
- `"Compare [conceito A] e [conceito B] discutidos no livro, destacando quando usar cada um."`
- `"Crie 5 perguntas de revisão sobre engenharia de dados baseadas nas fontes carregadas."`
- `"Quais são os erros mais comuns que iniciantes cometem ao tentar aplicar [conceito] na prática?"`

---

## 🔗 Projeto prático relacionado

Como parte da aplicação prática desse estudo, avaliei criticamente um projeto real de ETL que desenvolvi:
**ETL de Gestão de Estoque com Geração de Relatório em PowerPoint** — https://github.com/NickGMaia/ETL_gest-o_estoque

O feedback obtido no NotebookLM (documentado no Prompt 3 acima) está guiando as próximas evoluções desse projeto, como desacoplamento do pipeline, uso de armazenamento em nuvem, orquestração e testes de qualidade de dados.

---

## 🛠️ Ferramentas utilizadas
- [NotebookLM](https://notebooklm.google.com/)
- GitHub (versionamento e portfólio)

## ✍️ Autor
Nicolas Garcia Soto Maia

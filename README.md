# Case Técnico — Analista de Dados | Produto & Growth (the news)

Análise completa do comportamento dos usuários do **Palavritas**, jogo diário do the news, desenvolvida como parte do processo seletivo para a vaga de **Analista de Dados | Produto & Growth**.

O objetivo do projeto foi identificar os principais fatores associados ao retorno dos usuários no dia seguinte e à retenção após 30 dias, transformando os achados em recomendações práticas para o time de Produto.

---

# Objetivo do Projeto

Responder à seguinte pergunta de negócio:

> **"O que está determinando se um usuário volta a jogar — e o que podemos fazer para aumentar isso?"**

Para isso, o projeto foi dividido em cinco etapas:

- Business Understanding
- Data Understanding
- Data Preparation
- Análise Exploratória
- Testes Estatísticos
- Recomendações de Produto

---

# Arquivos do projeto

| Arquivo | Descrição |
|----------|-----------|
| `Palavritas_Retention_Analysiss.ipynb` | Notebook contendo toda a análise, limpeza dos dados e desenvolvimento do case |
| `Relatorio_Case_TheNews.docx` | Documento executivo contendo diagnóstico, achados e propostas |
| `README.md` | Resumo do projeto |
| `Dashboard_Palavritas.pbix` *(opcional)* | Dashboard desenvolvido no Power BI |

---

# Links

**Relatório completo (Google Docs)**

**[relatório](https://docs.google.com/document/d/1qjVVkGRc4TD5vZ6iykZSXAKpP_gi4kSVkBott_vG0lU/edit?tab=t.0#heading=h.l54j4hyesunp)**

---

**Dashboard Interativo**

**[dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTljZDM3Y2ItYTZkMC00ZTBlLTkzZDItZWU2MzRiMDBiMzg1IiwidCI6ImMzODRkN2Y5LTdhNDEtNDZiOS04ZTRjLWQzOTJlMGU4Zjc4OSJ9)**

**Notebook Online (Google Colab)**

**[Notebook](https://colab.research.google.com/drive/179VHk6DftH5vhx0YW_a8wJ4VJ2XzBt9_#scrollTo=X5Gn-zJDVHCn)**

---

# Dataset

Foram utilizados os três conjuntos de dados disponibilizados no desafio:

- **palavritas_sessions**
- **palavritas_attempts**
- **user_profile**

Os dados representam informações fictícias sobre o comportamento dos usuários do jogo Palavritas e seu perfil.

---

# Principais etapas da análise

## 1. Diagnóstico e preparação dos dados

Antes das análises exploratórias foi realizada uma etapa completa de diagnóstico dos dados.

Entre os principais problemas identificados estavam:

- registros duplicados;
- sessões com quantidade de tentativas inválidas;
- tempos negativos;
- valores ausentes;
- inconsistências de padronização;
- datas em formatos diferentes;
- problemas de integridade entre tabelas.

Todas as decisões de tratamento foram documentadas e fundamentadas utilizando evidências presentes nos próprios dados.

---

## 2. Análise Exploratória

Foram investigados diversos fatores relacionados à retenção dos usuários, incluindo:

- horário de jogo;
- abertura da newsletter;
- sequência de dias (streak);
- dispositivo utilizado;
- palavra do dia;
- tempo de conclusão da partida;
- perfil demográfico;
- características profissionais;
- hábitos de consumo.

Também foi desenvolvido um dashboard executivo para facilitar a visualização dos resultados.

---

## 3. Testes Estatísticos

Para complementar a análise exploratória foram aplicados:

- Teste Qui-Quadrado de Independência;
- Coeficiente de Cramer's V.

O objetivo foi avaliar se as diferenças observadas possuíam evidências estatísticas de associação com os indicadores de retenção.

---

## 4. Principais Insights

Entre os principais achados do projeto destacam-se:

- usuários que abriram a newsletter antes de jogar apresentaram maior retenção em 30 dias;
- usuários com maiores sequências (streak) apresentaram maior probabilidade de retornar no dia seguinte;
- o período do dia em que o usuário costuma jogar apresentou associação com a retenção;
- nenhuma variável isoladamente explicou o comportamento dos usuários, indicando que a retenção depende da combinação de múltiplos fatores.

---

## 5. Recomendações de Produto

Com base nas análises foram propostas três hipóteses para experimentação:

- sincronizar o desafio diário com a newsletter;
- fortalecer o mecanismo de streak utilizando recompensas progressivas;
- enviar notificações personalizadas considerando o horário habitual de jogo do usuário.

Cada proposta foi acompanhada de hipótese, ação sugerida e critérios objetivos de sucesso.

---

# Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Power BI
- Google Colab

---

# Autor

**Márlon Almeida**

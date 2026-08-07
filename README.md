# Case Técnico — Analista de Dados | Produto & Growth (the news)

Análise completa do comportamento dos usuários do **Palavritas**, jogo diário do the news, desenvolvida como parte do processo seletivo para a vaga de **Analista de Dados | Produto & Growth**.

O objetivo do projeto foi identificar os principais fatores associados ao retorno dos usuários no dia seguinte e à retenção após 30 dias, transformando os achados em recomendações práticas para o time de Produto.

---

# Objetivo do Projeto

O projeto teve como objetivo identificar os principais fatores associados ao retorno dos usuários no dia seguinte e à retenção após 30 dias no jogo Palavritas, respondendo à seguinte pergunta de negócio:

"O que está determinando se um usuário volta a jogar e o que podemos fazer para aumentar isso?"

Para isso, foram analisados diferentes aspectos do comportamento dos usuários, complementando a análise exploratória com testes estatísticos para validar as associações encontradas.

---

# Links

**Relatório completo (Google Docs)**

**[Relatório](https://docs.google.com/document/d/1qjVVkGRc4TD5vZ6iykZSXAKpP_gi4kSVkBott_vG0lU/edit?tab=t.0#heading=h.l54j4hyesunp)**

**Artigo Medium**

**[Artigo Medium](https://medium.com/@marlonm.almeida/o-que-faz-um-usu%C3%A1rio-voltar-uma-an%C3%A1lise-de-reten%C3%A7%C3%A3o-do-palavritas-2d23d5271d30?postPublishedType=repub)**

---

**Dashboard Interativo**

**[Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWVjMjZmZWMtNDZjNC00ODVkLWIwY2QtMWZhNzQ3NjMyNTBhIiwidCI6IjY0Zjk5OWRmLTM4NDktNDU0OS05YWMyLWY1ZDc4NTdjNTlhYyJ9)**

**Notebook Online (Google Colab)**

**[Notebook](https://colab.research.google.com/drive/179VHk6DftH5vhx0YW_a8wJ4VJ2XzBt9_#scrollTo=X5Gn-zJDVHCn)**

---

## 4. Principais Insights

Entre os principais achados do projeto destacam-se:

1. usuários que abriram a newsletter antes de jogar apresentaram maior retenção em 30 dias;
   
    <img width="409" height="416" alt="image" src="https://github.com/user-attachments/assets/ef2799f6-95fe-4f92-a89b-8768ae073be5" />

2. usuários com maiores sequências (streak) apresentaram maior probabilidade de retornar no dia seguinte;

    <img width="680" height="200" alt="image" src="https://github.com/user-attachments/assets/603bee13-704b-4808-ba04-18b472001fd5" />

3. o período do dia em que o usuário costuma jogar apresentou associação com a retenção;

    <img width="708" height="403" alt="image" src="https://github.com/user-attachments/assets/7db97c85-ca4b-4ce7-8a79-c3f2d3451701" />

nenhuma variável isoladamente explicou o comportamento dos usuários, indicando que a retenção depende da combinação de múltiplos fatores.

---

## 5. Recomendações de Produto

Com base nas análises foram propostas três hipóteses para experimentação:

- sincronizar o desafio diário com a newsletter;
- fortalecer o mecanismo de streak utilizando recompensas progressivas;
- enviar notificações personalizadas considerando o horário habitual de jogo do usuário.

Cada proposta foi acompanhada de hipótese, ação sugerida e critérios objetivos de sucesso.

---

## 6. Resultado de Negócio

Partindo das hipóteses já levantadas nas propostas, o ganho potencial a ser
validado via teste A/B é:

- **Newsletter (Propostas 1 e 3):** a cada 100 usuários que passarem a abrir
  a newsletter antes de jogar, cerca de **7 a mais** ficam ativos 30 dias
  depois — efeito reforçado pelo horário de envio (6h06), que já cai na
  faixa (6h–8h) de maior retenção.
- **Sequência de dias / streak (Proposta 2):** a cada 100 usuários que
  atingirem uma sequência de 4 dias ou mais, cerca de **6 a mais** voltam a
  jogar no dia seguinte.

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

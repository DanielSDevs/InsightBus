# 🚍 InsightBus – Segmentação Inteligente de Clientes

## 👨‍💻 Autores
- Daniel Silva Alves  
- Jean Ferreira dos Santos  
- Matheus Camati Velkis Toledo Piza 

---

## 📌 Contextualização
A **ClickBus**, maior plataforma online de venda de passagens rodoviárias do Brasil, recebe mais de **170 mil visitantes diários**.  
Apesar desse volume, ainda enfrenta dificuldades em **personalizar a jornada do cliente** devido à falta de segmentação clara baseada em comportamento de compra.  
Isso limita o alcance e a efetividade das campanhas de marketing e relacionamento.  

---

## ❗ Problema
A ClickBus não categoriza seus clientes com base no histórico de compra, dificultando:
- Criação de campanhas personalizadas  
- Fidelização de usuários  
- Melhoria da experiência no app  

---

## 💡 Solução Proposta – InsightBus
O **InsightBus** é um **dashboard interativo** que:  
- Segmenta clientes em **perfis comportamentais** (ex.: Econômico, Corporativo).  
- Apresenta **previsões simples**: probabilidade de recompra e sugestão de destinos prováveis.  
- Oferece suporte a decisões estratégicas de marketing e produto.  

---

## ⚙️ Proposta Técnica
- **Clusterização**: `scikit-learn` (K-Means, DBSCAN) + regras heurísticas  
- **Predição**: regressão linear simples e scorecards  
- **Visualização**: [Looker Studio](https://lookerstudio.google.com/)  
- **Armazenamento**: CSV local + [Google Cloud Storage](https://cloud.google.com/storage) / [BigQuery](https://cloud.google.com/bigquery)  
- **Ambiente**: [Google Colab](https://colab.research.google.com/) + [GitHub](https://github.com)  

---

## 🎯 Público-Alvo
- **Clientes da ClickBus**: experiência personalizada com promoções e destinos adequados.  
- **Equipes de marketing/growth/produto**: apoio a decisões estratégicas baseadas em dados.  
- **Usuários do app**: jornada mais personalizada e engajante.  

---

## 📊 Impacto Esperado
- Campanhas de marketing mais **precisas** e com menos desperdício.  
- Maior **engajamento** com o app.  
- **Redução de churn**.  
- Base sólida para futuras soluções preditivas.  

---

## ✅ Benefícios
- Aumento da **taxa de conversão** em campanhas promocionais.  
- Crescimento da base de **clientes recorrentes**.  
- Direcionamento mais assertivo de campanhas.  

---

## 🆚 Comparativo com Concorrentes

| Plataforma | Foco | Diferença em relação ao InsightBus |
|------------|------|------------------------------------|
| [Amadeus Travel Intelligence](https://amadeus.com) | Dados do setor de viagens | Solução global e ampla, não focada no cliente ClickBus |
| [RateGain](https://rategain.com) | Pricing e demanda (hotéis/transportes) | Voltado para precificação, não segmentação comportamental |
| [ForwardKeys](https://forwardkeys.com) | Previsões de viagens com big data | Abordagem macro, enquanto o InsightBus é direto e aplicável ao cliente da ClickBus |

---

## 🛠️ Stack do MVP

| Etapa | Ferramenta |
|-------|------------|
| Manipulação de dados | [Python](https://www.python.org/) – pandas, numpy |
| Segmentação | [scikit-learn](https://scikit-learn.org/) |
| Predição simples | scikit-learn (regressão linear) |
| Visualização/Dashboard | [Looker Studio](https://lookerstudio.google.com/) |
| Armazenamento local | CSV |
| Armazenamento escalável | [Google Cloud Storage](https://cloud.google.com/storage), [BigQuery](https://cloud.google.com/bigquery) |
| Prototipação visual | [Figma](https://figma.com) |
| Organização da equipe |

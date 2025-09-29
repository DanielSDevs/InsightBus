<p align="center">
  <img src="https://github.com/user-attachments/assets/e93a8441-3620-4a40-a7b5-7729b093a364" alt="InsightBus Logo" width="45%"/>
  <img src="https://github.com/user-attachments/assets/b2501ba0-206a-48ad-adb6-517673099a61" alt="Dashboard InsightBus" width="45%"/>
</p>


# 🚍 InsightBus – Segmentação Inteligente de Clientes

## 👨‍💻 Autores
- TURMA: 1TSCPW
- DANIEL SILVA ALVES - RM565770
- JEAN FERREIRA DOS SANTOS - RM564347
- MATHEUS CAMATI VELKIS TOLEDO PIZA - RM562991

---

## 🔗 Links do Projeto

<p align="center">
  - 🎥 [Vídeo Pitch](https://www.youtube.com/watch?v=hJtzmacejsQ) 
  - 📊 [Dashboard](https://lookerstudio.google.com/reporting/568094d8-701c-4f43-a50e-d9685809a0b5/page/p_noooayy3vd)
</p>

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
- Cálculo da próxima compra e target binário (0/1) para recompra em 30 dias
- **Visualização**: [Looker Studio](https://lookerstudio.google.com/)  
- **Armazenamento**: CSV local + [Google Cloud Storage](https://cloud.google.com/storage) / [BigQuery](https://cloud.google.com/bigquery)  
- **Ambiente**: [Google Colab](https://colab.research.google.com/) + [GitHub](https://github.com)

<p align="center">
  <img src="https://github.com/user-attachments/assets/f4ac6e4b-aef9-4608-b962-8c772bc28b9e" alt="Captura de tela" width="800"/>
</p>


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

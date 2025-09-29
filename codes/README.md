# InsightBus – Segmentação e Previsão de Clientes

## Descrição
Este projeto realiza análise e clusterização de clientes da ClickBus, com o objetivo de:

1. **Segmentar clientes** por comportamento de compra.  
2. **Prever recompra** em até 30 dias.  
3. **Identificar destinos mais prováveis** por perfil.

---

## Scripts

### `segmentacao_clientes.py`
- **Objetivo:** Agrupar clientes em perfis comportamentais.
- **Etapas:**
  - Carregamento e limpeza de dados (`dados_limpos.csv`)  
  - Criação de indicadores: `dia_semana`, `feriado_fds`  
  - Agrupamento por cliente e cálculo de métricas:
    - Ticket médio  
    - Quantidade de destinos  
    - Percentual de viagens em feriados/fds  
  - Normalização e clusterização com **KMeans**  
  - Visualização de clusters e centróides  
  - Geração do CSV `clientes_clusterizados.csv`

### `previsao_recompra_destinos.py`
- **Objetivo:** Prever recompra e destinos prováveis por perfil.
- **Etapas:**
  - Carregamento de `clientes_clusterizados.csv`  
  - Cálculo da próxima compra e target binário (`0/1`) para recompra em 30 dias  
  - Probabilidade de recompra por perfil  
  - Percentual de destinos mais visitados por cluster  
  - Amostragem de 1000 registros por cluster  
  - Geração de CSVs finais: `Amostra_InsightBus.csv` e `InsightBus.csv`

---

## Requisitos
- Python 3.x  
- Bibliotecas:
```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
holidays
google-colab


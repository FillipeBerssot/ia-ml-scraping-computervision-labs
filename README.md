# Estudo / Desafio: IA/ML + Web Scraping + Visão Computacional (Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/drive/1hhowOs12gUiIKeVFFQctOpyhdMdJ0qpH#scrollTo=5a0f113c)

**O que tem aqui (em um só notebook):**
- **Dados & ML:** limpeza simples, EDA, feature engineering; Regressão (preço) e Classificação (caro ≥ mediana).
- **Web Scraping:** `requests` + `BeautifulSoup` no *quotes.toscrape.com*.
- **Visão Computacional:** Gaussian Blur, Canny, equalização (cinza e HSV→V), detecção de movimento (MOG2).

## Como executar
1. Clique no badge **Open in Colab** (acima).  
2. Execute as células na ordem (o notebook baixa dados e vídeo por link).  
3. Se rodar local: `pip install -r requirements.txt` e abra o `.ipynb`.

## Resultados (preencha rápido)
- **Regressão:** MAE=… | RMSE=… | R²=…  
- **Classificação:** Acc=… | Precision=… | Recall=… | F1=…  
- **CV:** bordas (Canny) e equalização destacam detalhes; MOG2 mostra movimento (máscara binária).

## Notas
- Notebook com saídas **limpas** para manter o repo leve.  
- Para manter o `.ipynb` pequeno, evite salvar com vídeos incorporados.


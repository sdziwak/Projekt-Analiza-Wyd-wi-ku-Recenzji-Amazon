# Analiza Wydźwięku Recenzji Amazon

## Opis projektu
Celem projektu jest przeprowadzenie analizy wydźwięku recenzji klientów na podstawie zbioru danych "Amazon Reviews for Sentiment Analysis". Główne zadanie to klasyfikacja recenzji jako pozytywnych lub negatywnych oraz stworzenie modeli klasyfikacyjnych, które pozwolą na skuteczne przewidywanie wydźwięku na podstawie treści tekstu.

## Zbiór danych
W projekcie wykorzystano publicznie dostępny zbiór danych "Amazon Reviews for Sentiment Analysis" dostępny na Kaggle. 
Dane zawierają oznaczone recenzje klientów:
- **__label__1**: Negatywny wydźwięk (recenzje 1- i 2-gwiazdkowe)
- **__label__2**: Pozytywny wydźwięk (recenzje 4- i 5-gwiazdkowe)

Recenzje neutralne (3-gwiazdkowe) zostały pominięte w zbiorze.

[Zbiór danych na Kaggle](https://www.kaggle.com/datasets/bittlingmayer/amazonreviews)

## Cele projektu
1. Eksploracja i wstępne przetwarzanie danych.
2. Budowa modeli klasyfikacyjnych do analizy wydźwięku recenzji.
3. Porównanie wyników modeli i ocena ich skuteczności.
4. Wizualizacja wyników i wniosków.

## Plan realizacji
1. **Eksploracja danych**:
   - Analiza struktury i rozkładu etykiet (pozytywne vs negatywne).
   - Wstępna analiza treści recenzji.

2. **Przetwarzanie danych**:
   - Czyszczenie tekstu (usuwanie znaków specjalnych, stopwords).
   - Tokenizacja i przekształcenie tekstu na reprezentację numeryczną (TF-IDF, embeddingi).

3. **Budowa modeli**:
   - Trenowanie modeli klasyfikacyjnych przy użyciu regresji logistycznej, SVM oraz Random Forest.
   - Ocena modeli przy użyciu metryk: accuracy, precision, recall, F1-score.

4. **Wizualizacja**:
   - Rozkład wydźwięku recenzji.
   - Ważność cech w modelach.
   - Macierz konfuzji dla najlepszego modelu.

## Narzędzia i technologie
- Python
- Biblioteki: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib
- Jupyter Notebook

# Algorytmy eksploracji danych

Notebook Jupyter w Pythonie prezentujący wybrane algorytmy Machine Learning z zakresu eksploracji danych — z wizualizacją wyników na rzeczywistych zbiorach danych.

## Zawartość

### 1. Techniki redukcji wymiarów
- **PCA** (Principal Component Analysis) — redukcja przestrzeni cech przy zachowaniu maksymalnej wariancji
- Standaryzacja danych z użyciem `StandardScaler`
- Wizualizacja składowych głównych

### 2. Klasteryzacja
- **K-Means** — grupowanie danych na podstawie podobieństwa
- Ocena jakości grupowania za pomocą **Silhouette Score**
- Wizualizacja klastrów

### 3. Klasyfikacja
- **Drzewo decyzyjne** (`DecisionTreeClassifier`) — uczenie nadzorowane
- Podział danych na zbiór treningowy i testowy (`train_test_split`)
- Ocena modelu: dokładność (`accuracy_score`), raport klasyfikacji, macierz pomyłek (`ConfusionMatrixDisplay`)
- Wizualizacja struktury drzewa (`plot_tree`)

### 4. Reguły asocjacyjne
- Wykrywanie zależności i wzorców współwystępowania w zbiorach danych

---

## Technologie i biblioteki

| Biblioteka | Zastosowanie |
|---|---|
| `pandas` | przetwarzanie i analiza danych |
| `numpy` | operacje na tablicach i obliczenia numeryczne |
| `matplotlib` | wizualizacje |
| `seaborn` | wizualizacje statystyczne |
| `scikit-learn` | algorytmy ML: PCA, KMeans, DecisionTree, metryki |
| `gdown` | pobieranie zbiorów danych z Google Drive |

---

## Zbiory danych

| Plik | Opis |
|------|------|
| `students_habits.csv` | Dane o nawykach studentów |
| `food_habits.csv` | Dane dotyczące nawyków żywieniowych |
| `Mall_Customers.csv` | Dane klientów centrum handlowego |

---

## Uruchomienie

1. Otwórz notebook w środowisku z dostępem do internetu (np. Google Colab lub lokalny Jupyter).
2. Uruchom pierwszą komórkę — `gdown` zainstaluje się automatycznie, a dane zostaną pobrane z Google Drive.
3. Uruchamiaj kolejne sekcje notebooka według kolejności.

```bash
# Jeśli uruchamiasz lokalnie:
pip install jupyter pandas numpy matplotlib seaborn scikit-learn gdown
jupyter notebook
```

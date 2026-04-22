# Klasyfikacja wyników meczów piłkarskich – ML Project

## Opis projektu
Projekt analizuje statystyki meczowe (strzały, rzuty rożne itp.) z angielskiej Premier League w celu sklasyfikowania wyniku meczu (Gospodarz/Remis/Gość). Głównym celem była analiza "post-factum" – sprawdzenie, czy statystyki meczowe rzeczywiście odzwierciedlają końcowy wynik oraz porównanie dwóch różnych podejść algorytmicznych.

## Technologie i Biblioteki
* **Język:** Python 3.x
* **Biblioteki:** Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Matplotlib, Seaborn.
* **Dane:** Statystyki z serwisu [football-data.co.uk](https://www.football-data.co.uk/englandm.php).

## Metodologia i Feature Engineering
W projekcie skupiłem się na przetworzeniu surowych danych statystycznych, tworząc nowe cechy (Feature Engineering), które lepiej oddają przebieg meczu. Porównano dwa modele:
1. **Model płytki:** Random Forest
2. **Model głęboki:** Sieć Neuronowa (Multilayer Perceptron)

## Wyniki
Na podstawie przeprowadzonych testów, lepszą skuteczność w klasyfikacji osiągnął model **Random Forest**:
* **Random Forest Accuracy:** 61.90%
* **Neural Network Accuracy:** 52.38%

## Struktura plików
* `Projekt_Uczenie_Maszynowe_Piłkarski_Feature_Engineering.ipynb` – Główny notatnik z kodem i analizą.
* `E0.csv` – Zbiór danych (Premier League).
* `requirements.txt` – Lista bibliotek potrzebnych do uruchomienia projektu.

## Jak uruchomić
1. Sklonuj repozytorium.
2. Zainstaluj wymagane biblioteki: `pip install -r requirements.txt`.
3. Otwórz notatnik w Jupyter Notebook lub Google Colab.

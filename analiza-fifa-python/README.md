# Analiza zawodników i predykcja wartości w FIFA 22

Projekt dedykowany analizie atrybutów piłkarzy w grze FIFA 22, weryfikacji hipotez statystycznych oraz budowie modeli uczenia maszynowego prognozujących wartość rynkową zawodników.

## Technologie i narzędzia
* **Język:** Python
* **Środowisko:** Jupyter Notebook (`.ipynb`), VS Code
* **Biblioteki:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Metody:** Czyszczenie danych (Data Cleaning), EDA, analiza korelacji, testy statystyczne, uczenie maszynowe (Regresja / ML)

## Zakres analizy
* **Profilowanie pozycji i narodowości:** Porównanie parametrów fizycznych i technicznych piłkarzy w zależności od pozycji na boisku oraz kraju pochodzenia.
* **Rozkłady i statystyki opisowe:** Analiza wieku, oceny ogólnej (Overall), potencjału oraz logarytmicznego rozkładu wartości rynkowej.
* **Macierz korelacji:** Identyfikacja kluczowych atrybutów wpływających na cenę zawodników.
* **Weryfikacja hipotez statystycznych:**
  * Test Shapiro-Wilka (badanie normalności rozkładu wyceny).
  * Test t-Studenta (porównanie wartości lewych i prawych obrońców).
  * Test Manna-Whitneya (porównanie umiejętności napastników i środkowych obrońców).
* **Modelowanie predykcyjne:** Budowa i ewaluacja modeli uczenia maszynowego szacujących wartość rynkową graczy.

## Opis plików
* `predykcja_fifa.ipynb` – notebook z pełnym kodem (analiza danych, wykresy, testy statystyczne i modele ML).
* `FIFA 22.csv` – zbiór danych zawierający kompletne statystyki piłkarzy.

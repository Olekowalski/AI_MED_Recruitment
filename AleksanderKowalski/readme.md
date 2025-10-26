Ten notatnik demonstruje proces tworzenia i oceny modelu klasyfikacyjnego opartego na drzewie decyzyjnym (DecisionTreeClassifier) przy użyciu biblioteki scikit-learn.

Główne kroki obejmują:

1. Ładowanie danych: Wczytanie danych z pliku CSV.
2. Przygotowanie danych: Podział danych na cechy (X) i zmienną docelową (y), a następnie podział na zestawy treningowy i testowy.
3. Skalowanie danych: Przeskalowanie cech przy użyciu StandardScaler.
4. Strojenie hiperparametrów: Wykorzystanie GridSearchCV do znalezienia najlepszych parametrów dla modelu drzewa decyzyjnego, zoptymalizowanego pod kątem metryki F1.
5. Trenowanie modelu: Trenowanie modelu drzewa decyzyjnego z najlepszymi znalezionymi parametrami.
6. Ocena modelu: Ocena wydajności modelu na zestawie testowym przy użyciu raportu klasyfikacji.
  
    Notatnik ilustruje standardowy przepływ pracy w uczeniu maszynowym, ze szczególnym uwzględnieniem radzenia sobie z potencjalnymi problemami związanymi z niezbalansowanymi danymi (poprzez wybór metryki F1 w GridSearchCV).

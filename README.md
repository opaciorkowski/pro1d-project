# Projekt: Rozpoznanie Liter

## Autor: Duy Vu Thanh, Oskar Paciorkowski

### 1. Źródło Danych
Dane użyte w projekcie pochodzą z [bazy danych UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/letter+recognition). Zbiór danych zawiera litery alfabetu angielskiego napisane w dwudziestu różnych czcionkach. Litery są reprezentowane jako mapy pikseli czarno-białych, z losowymi deformacjami. Po przekształceniu, litery są opisane za pomocą 16 atrybutów numerycznych o wartościach od 0 do 15. Zbiór danych zawiera 20 000 przykładów.

### 2. Opis Zadania
Celem badania jest stworzenie klasyfikatora zdolnego do rozpoznawania liter na podstawie dostarczonych danych. Zbiór treningowy składa się z 16 000 pierwszych liter, a zbiór testowy z 4 000 pozostałych liter.

### 3. Metoda i Implementacja
a) **Normalizacja Atrybutów:** Wartości atrybutów zostaną znormalizowane, aby doprowadzić je do zakresu (0,1).

b) **Wybór Klasyfikatorów:**
   - k-NN (k-najbliższych sąsiadów)
   - Sieć Neuronowa

c) **Testowanie Skuteczności:**
   - Skuteczność każdego z wybranych klasyfikatorów będzie testowana, a ich trafności w klasyfikacji liter będą porównywane.

### 4. Model Testowania
   - **Zbiór Treningowy:** Pierwsze 16 000 liter (wierszy) w pliku 'letter-recognition.data'.
   - **Zbiór Testowy:** Pozostałe 4 000 liter w tym samym pliku.

### 5. Miara Oceny
Miara oceny skuteczności klasyfikacji będzie oparta na trafności (accuracy) klasyfikatora na zbiorze testowym. 

Projekt ma na celu opracowanie efektywnego systemu rozpoznawania liter z wykorzystaniem różnych klasyfikatorów i ocenę ich skuteczności w kontekście klasyfikacji liter alfabetu angielskiego.

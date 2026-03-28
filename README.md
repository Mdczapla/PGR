# PGR: Procedural Room & Dungeon Generator 🏰⛓️

Zaawansowany system **PGR (Procedural Generating Room)** stworzony w **Unreal Engine 5**. Projekt wykorzystuje **PCG Framework** oraz komponentów **Spline** do dynamicznego tworzenia połączonych struktur pomieszczeń, tworząc unikalne układy poziomów przy każdym uruchomieniu.

## 🧱 O projekcie: Logika PCG + Spline
System generowania opiera się na inteligentnym łączeniu dwóch technologii:
1. **Splines (Kontury):** Każdy pokój jest definiowany przez krzywe spline, co pozwala na tworzenie pomieszczeń o dowolnych, nieliniowych kształtach.
2. **PCG Graph:** Odpowiada za proceduralne wypełnianie wnętrz (ściany, podłoga) oraz dopasowywanie elementów konstrukcyjnych do obrysu zdefiniowanego przez spline.

## 🤖 Algorytm Generowania Mapy
Serce systemu stanowi zaawansowany generator poziomów, który:
* **Weryfikuje wyjścia (Exit Checking):** System analizuje dostępne punkty połączeń w istniejących pokojach.
* **Walidacja przestrzeni (Bounds Checking):** Przed wygenerowaniem nowego pokoju, algorytm sprawdza, czy w danym miejscu jest wystarczająco dużo wolnej przestrzeni, aby uniknąć kolizji i nakładania się struktur.

## 🚀 Kluczowe cechy
* **Pełna Proceduralność:** Generowanie całych lochów/budynków na podstawie jednego kliknięcia.
* **Modyfikowalne Ustawienia:** Każdy pokój posiada zestaw parametrów (widocznych w panelu Details).
* **Mapa "PCG":** Gotowe środowisko testowe prezentujące pełne możliwości algorytmu.

## 🛠 Technologie
* **Silnik:** Unreal Engine 5
* **Framework:** PCG (Procedural Content Generation)
* **Logika:** UE5 Blueprints & Spline Components

## 💻 Jak uruchomić
1. Sklonuj repozytorium do folderu projektowego.
2. Otwórz projekt w **Unreal Engine 5**.
3. Załaduj mapę o nazwie **PCG**.
4. Znajdź na scenie Blueprint generatora i użyj funkcji generowania (lub naciśnij **Play**), aby zobaczyć proces tworzenia mapy w czasie rzeczywistym.

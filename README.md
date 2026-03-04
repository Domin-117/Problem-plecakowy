# AiSD — Projekt 5: Problem plecakowy

Implementacja problemu plecakowego (0/1 Knapsack Problem) w Pythonie z dwoma podejściami: programowaniem dynamicznym oraz brute force.

## Opis

Projekt zawiera:
- Generowanie losowych danych wejściowych
- Rozwiązanie problemu plecakowego metodą programowania dynamicznego (DP)
- Rozwiązanie problemu plecakowego metodą brute force
- Benchmarki porównujące czas wykonania obu metod w zależności od liczby przedmiotów (n) i pojemności plecaka (C)

## Pliki

- `plecak.py`: Główny plik z implementacją algorytmów
- `benchmark.py`: Skrypt do przeprowadzania benchmarków
- `dane.txt`: Przykładowe dane wejściowe
- `benchmark_dane.txt`: Dane używane podczas benchmarków
- `benchmark_n_dp.csv`, `benchmark_n_bf.csv`: Wyniki benchmarków dla zmiennej n
- `benchmark_C_dp.csv`, `benchmark_C_bf.csv`: Wyniki benchmarków dla zmiennej C
- `Sprawozdanie/`: Folder ze sprawozdaniem w formacie LaTeX

## Jak uruchomić

Uruchom główny program:
   ```
   python3 plecak.py
   ```
   To wygeneruje dane, rozwiąże problem obiema metodami i wyświetli wyniki.

Uruchom benchmarki:
   ```
   python3 benchmark.py
   ```
   To przeprowadzi benchmarki i zapisze wyniki do plików CSV.


## Sprawozdanie

Sprawozdanie znajduje się w folderze `Sprawozdanie/`. Zawiera wyniki benchmarków.

Autorzy
Projekt i sprawozdanie: Dominik Fischer, Oliwer Miller

## Zasady konkursu SRD
### Zespoły
Należy dobrać się w zespoły złożone z 1-3 osób. Proszę nazwać zespół (nazwa pojawi się w tabeli z wynikami). Proszę nie używać danych osobowych w nazwach. 

### Zbiór danych i cel konkursu
Celem konkursu jest uzyskanie jak największego **accuracy** (procent poprawnie zaklasyfikowanych obserwacji [TP+TN/(TP+TN+FP+FN)]) w klasyfikacji zmiennej celu **IsIPA**. Do stworzenia modelu proszę wykorzystać zbiór danych **IPA.csv**, natomiast finalną predykcję należy wykonać na zbiorze **IPA_test.csv**. Opis zbioru znajduje się w pliku **IPA_description.txt**.

### Przesłanie i forma wyników
Wyniki należy przesłać na adres lukasz.krainski123@gmail.com do godziny 22:00 (grupy rozpoczynające o 19:00) lub 20:10 (grupy rozpoczynające o 17:10). Wiadomości otrzymane po określonych godzinach nie będą przyjmowane. W treści maila należy podać nazwę grupy oraz imiona i nazwiska członków. Jako załączniki należy zamieścić:
1. Skrypt R/Python/Julia ze stworzonym kodem
2. Plik CSV o nazwie **[nazwa_grupy]_IPA_prediction.csv** zawierający jedną kolumnę z 5000 obserwacji (i opcjonalnym nagłówkiem) z wartościami 1/0 lub TRUE/FALSE oznaczających predykcję dla kolejnych wierszy ze zbioru testowego **IPA_test.csv**. 

Proszę dokładnie sprawdzić czy kolejność predykcji zgadza się z kolejnością obserwacji w zbiorze testowym.

Tabela z rankingiem zespołów pojawi się na GitHubie w poniższym pliku README. Najlepszy zespół otrzyma dodatkowe 5 punktów, kolejny 4 punkty, itd.

Życzę powodzenia. 

### Wyniki konkursu

**Grupa 3**

| Zespół           | Miejsce   | Accuracy | Język  | Algorytm                |
|------------------|-----------|----------|--------|-------------------------|
| Szalone Morświny | 1 (5pkt)  | 86.74%   | R      | Boosted Trees (XGBoost) |
| brjcap           | 2 (4pkt)  | 86.40%   | R      | Random Forest           |
| Czarne Konie     | 3 (3 pkt) | 86.36%   | Python | Random Forest           |
| Smoki            | 4 (2 pkt) | 86.04%   | R      | Boosted Trees ?         |
| Ciepła Kosa      | 5 (1 pkt) | 86.00%   | R      | CART                    |
| Dziki 2077       | 6 (0 pkt) | 85.94%   | R      | Boosted Trees (XGBoost) |

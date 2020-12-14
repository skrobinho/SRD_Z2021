## Zasady konkursu SRD
### Zespoły
Należy dobrać się w zespoły złożone z 1-3 osób. Proszę nazwać zespół (nazwa pojawi się w tabeli z wynikami). Proszę nie używać danych osobowych w nazwach. 

### Zbiór danych i cel konkursu
Celem konkursu jest uzyskanie jak największego **accuracy** (procent poprawnie zaklasyfikowanych obserwacji [TP+TN/(TP+TN+FP+FN)]) w klasyfikacji zmiennej celu **IsIPA**. Do stworzenia modelu proszę wykorzystać zbiór danych **IPA.csv**, natomiast finalną predykcję należy wykonać na zbiorze **IPA_test.csv**. Opis zbioru znajduje się w pliku **IPA_description.txt**.

### Wyniki
Wyniki należy przesłać na adres lukasz.krainski123@gmail.com do godziny 22:00 (grupy rozpoczynające o 19:00) lub 20:10 (grupy rozpoczynające o 17:10). Wiadomości otrzymane po określonych godzinach nie będą przyjmowane. W treści maila należy podać nazwę grupy oraz imiona i nazwiska członków. Jako załączniki należy zamieścić:
1. Skrypt R/Python/Julia ze stworzonym kodem
2. Plik CSV o nazwie **[nazwa_grupy]_IPA_prediction.csv** zawierający jedną kolumnę z 5000 obserwacji (i opcjonalnym nagłówkiem) z wartościami 1/0 lub TRUE/FALSE oznaczających predykcję dla kolejnych wierszy ze zbioru testowego **IPA_test.csv**. 

Proszę dokładnie sprawdzić czy kolejność predykcji zgadza się z kolejnością obserwacji w zbiorze testowym.

Tabela z rankingiem zespołów pojawi się na GitHubie w poniższym pliku README. Najlepszy zespół otrzyma dodatkowe 5 punktów, kolejny 4 punkty, itd.

Życzę powodzenia. 
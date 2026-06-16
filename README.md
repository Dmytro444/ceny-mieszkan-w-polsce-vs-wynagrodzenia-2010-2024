# Czy mieszkania w Polsce stają się coraz mniej przystępne? Analiza danych GUS za lata 2010-2024 dla 11 największych miast pod względem liczby ludności
Projekt analityczny mający na celu znalezienie odpowiedzi na pytanie, czy mieszkania w Polsce stają się coraz mniej przystępne dla przeciętnej osoby pracującej w tym kraju.

## Cel analizy
Weryfikacja hipotezy, czy ceny mieszkań w największych polskich miastach rosną szybciej niż wynagrodzenia, w wyniku czego mieszkania stają się coraz mniej dostępne dla osób pracujących w Polsce.

## Przegląd zbioru danych
12 tabel źródłowych transformowanych w 8 tabel modelu danych zorganizowanych w schemat galaktyczny (konstelacja faktów).

## Ramy analityczne
W trakcie analizy porównano następujące czynniki wpływające na ceny mieszkań oraz zdolność ludności do ich zakupu w wybranych miastach:
- podaż i popyt na rynku pierwotnym;
- liczba mieszkań a liczba ludności;
- dynamika inflacji i nakładów na budowę mieszkań a dynamika przeciętnych wydatków gospodarstw domowych;
- ceny mieszkań a przeciętne wynagrodzenia i mediana wynagrodzeń.

## Tech stack
- Excel (pliki z danymi źródłowymi pobranymi z Banku Danych Lokalnych GUS);
- Power Query (ekstrakcja, transformacja i ładowanie danych);
- Power BI (model danych, miary DAX oraz interaktywne dashboardy).

## Kluczowe wnioski
- **Rozwój zasobów mieszkaniowych wyprzedzał zmiany demograficzne** - we wszystkich analizowanych miastach liczba mieszkań rosła szybciej niż liczba ludności, co przełożyło się na poprawę wskaźników mieszkaniowych i spadek liczby osób przypadających na jedno mieszkanie.
- **Popyt na rynku pierwotnym nie nadążał za rosnącą podażą** - liczba mieszkań oddawanych do użytkowania była zazwyczaj wyższa od liczby mieszkań sprzedawanych, choć skala tego zjawiska różniła się pomiędzy miastami.
- **Ceny mieszkań rosły znacznie szybciej niż inflacja i koszty budowy** - w latach 2010-2024 wzrost cen mieszkań przekroczył zarówno dynamikę cen towarów i usług konsumpcyjnych, jak i wzrost kosztów budowy budynków mieszkalnych.
- **Wzrost przeciętnych wynagrodzeń nie przełożył się na poprawę dostępności mieszkań** - analiza mediany wynagrodzeń wskazuje, że ceny mieszkań rosły szybciej niż dochody mieszkańców, szczególnie na rynku wtórnym.
- **Najsilniej drożały małe mieszkania** - lokale o powierzchni do 40 m2 odnotowały najwyższą dynamikę cen, co może świadczyć o rosnącym popycie na mniejsze i relatywnie bardziej dostępne cenowo nieruchomości.
- **Dostępność mieszkań pozostawała silnie zróżnicowana regionalnie** - najmniej korzystna relacja cen mieszkań do wynagrodzeń występowała w Warszawie, podczas gdy relatywnie najwyższą dostępność mieszkań odnotowano w Bydgoszczy, Łodzi i Katowicach.

## Źródła danych
- [GUS - Bank Danych Lokalnych](https://bdl.stat.gov.pl/bdl/dane/podgrup/temat)
- [Wynagrodzenia Polaków w 2010 roku. Podsumowanie Ogólnopolskiego Badania Wynagrodzeń - wynagrodzenia.pl](https://wynagrodzenia.pl/artykul/wynagrodzenia-polakow-w-2010-roku-podsumowanie-ogolnopolskiego-badania-wynagrodzen_1)

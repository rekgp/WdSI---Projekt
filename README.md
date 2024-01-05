# WdSI---Projekt
Projekt zaliczeniowy z przedmiotu Wprowadzenie do sztucznej inteligencji

#

# 1: Opis rzeczywistego problemu

## Identyfikacja kierunku jazdy ciągnika transportowego

#### Efekt:
Określenie kierunku jazdy ~~i/lub identyfikacji oznaczenia~~ ciągnika transportowego.
#### Motywacja:
Potrzeba pomiaru i kontroli czasu dostaw części potrzebnych do produkcji.
Możliwość skorzystania z istniejącej infrastruktury.
Brak potrzeby budowy nowego systemu kontroli pozycji pojazdów.
Stosunkowo niska cena realizacji w porównaniu z innymi typami pomiaru.
#### Dane wejściowe
Zdjęcia lub transmisja video z kamery ~~lub grafiki wygenerowane przez program typu blender~~. 
#### Dane wyjściowe
Kierunek jazdy wraz z danymi dotyczącymi czasu ~~i oznaczenia~~.
#### Symplifikacja
Ze względu na możliwy brak dostępu do rzeczywistych danych projekt zostanie zrealizowany dla rozpoznawania kierunku jazdy samochodów.

# 2: State of art
W erze przemysłu 4.0, precyzyjne zarządzanie liniami produkcyjnymi i logistyka wewnętrzna stają się kluczowymi czynnikami efektywności i innowacyjności. Identyfikacja kierunku jazdy ciągników transportowych oraz pomiar czasu dostaw to kluczowe wyzwania w optymalizacji produkcji. Przedstawione metody reprezentują najnowsze osiągnięcia w dziedzinie sztucznej inteligencji i analizy danych, dostosowane do specyficznych potrzeb zamkniętych przestrzeni produkcyjnych.

## Systemy wizyjne oparte na rozpoznawaniu wzorców:

Mocne strony: Systemy te wykorzystują kamery do śledzenia pojazdów i identyfikacji ich kierunku ruchu poprzez analizę wzorców ruchu i porównywanie ich z bazą danych. Technologia ta jest dość dokładna, znana oraz pewna co umożliwia jej zastosowanie w różnych warunkach oświetleniowych.
Słabe strony: Wymagają one jednak wysokiej jakości obrazów i są podatne na błędy w przypadku przeszkód lub niejednoznacznych sytuacji na trasie.

## Sieci neuronowe i uczenie głębokie:

Mocne strony: Metody te uczą się z dużej ilości danych i są w stanie identyfikować subtelne różnice w kierunkach jazdy pojazdów. Mogą przewidywać i rozpoznawać złożone wzorce ruchu dzięki głębokiemu uczeniu się.
Słabe strony: Wymagają one znacznych zasobów obliczeniowych i dużej ilości danych do nauki. Ponadto, mogą być trudniejsze w implementacji i wymagają regularnych aktualizacji w miarę zmieniających się warunków.

## Rozpoznawanie wzorców przy użyciu ultradźwięków lub lidaru z wykorzystaniem metod sztucznej inteligencji:

Mocne strony: Technologie ultradźwiękowe lub lidarowe są wykorzystywane do generowania danych o otoczeniu, które następnie są analizowane przy użyciu zaawansowanych algorytmów sztucznej inteligencji. Ultradźwięki i lidar działają przez emisję fal, które odbijają się od obiektów i wracają do sensora, tworząc mapę otoczenia. Wysoka dokładność, odporność na warunki środowiskowe, zdolność do analizy w czasie rzeczywistym oraz adaptacyjność są ich mocnymi stronami.
Słabe strony: Jednakże, mają też swoje słabe strony, takie jak koszty implementacji i konserwacji, techniczna złożoność, wymagania sprzętowe oraz ograniczenia w śledzeniu wielu obiektów, szczególnie w zatłoczonych środowiskach. Wysokie koszty, konieczność regularnej konserwacji oraz złożoność techniczna mogą nie być optymalnym rozwiązaniem.

Wybór odpowiedniej metody zależy od wielu czynników, w tym od specyfiki produkcji, warunków środowiskowych oraz dostępnych zasobów. Integracja tych technologii może znacząco przyczynić się do poprawy efektywności operacyjnej, minimalizacji błędów i zwiększenia przejrzystości procesów produkcyjnych. Dalszy rozwój sztucznej inteligencji i technologii analizy danych będzie kontynuować trend wzrostu możliwości monitorowania i automatyzacji w przemyśle, dostarczając coraz bardziej zaawansowanych narzędzi do zarządzania produkcją i logistyką wewnętrzną. W miarę rozwoju tych technologii, możemy oczekiwać jeszcze większej integracji i automatyzacji w przemyśle, prowadzącej do jeszcze wyższej efektywności i adaptacji do szybko zmieniających się warunków rynkowych.


# Realizacja
Bartosz Śrama  
Wojciech Tyc

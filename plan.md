# Część pierwsza - czym jest analiza sygnałów

## Teoria
1. Sygnał -> temporal vs spatial sygnal, co nazywamy sygnałem
2. Twierdzenie o próbkowaniu
3. Wspomnieć że to bardzo szeroki temat i jest wiele algorytmów a my będziemy korzystać z FFT
4. FFT -> pokazać całkę z transformatą fouriera

## Praktyka
1. import bibliotek
2. Generowanie przykładowego sygnału z zaszumieniem
3. Jak w takim razie przybliżyć sygnał ciągły?

# Część druga - rekonstrukcja sygnału ciągłego
WRGYWAMY DŹWIĘK - RICK ROLL?
## Teoria 
Możliwe podejścia

### Intuicja i rekonstrukcja w dziedzinie częstotliwości - Frequency-Domain Filtering
czyli to z początku

### Ograniczenia FFT
Rozwiązania ograniczeń - TEORIA:

1. Funkcja okna -> są różne; The main purpose of window
functions is to reduce spectral leakage between nearby frequency bins, which occur
in discrete Fourier transform computation when the signal contains components with
periods that are not exactly divisible with the sampling period.
2. Spektrogram


### Filtry splotowe teoria + praktyka (bardziej praktyka)
1. Twierdzenie o splocie
2. Znowu rekonstrukcja

### Filtry FIR i IIR
ALE splot niemożliwy w praktyce

Pokazać jak się różnią te wszystkie podejścia na jakimś grafie idk

# Część trzecia 
Zastosowania praktyczne
1. Muzyka (noise cancellation, autotune)
2. Obrazy (nakładanie filtrów) -> NIECH ZROBIą DRUGI FILTR 
3. Można ew o geografii, chemii

# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to Topologia która charakteryzuje się tym, że wszystkie urządzenia (np. komputery, drukarki) dołączane są do jednego wspólnego kabla koncentrycznego, który obsługuje tylko jeden kanał.
  - Wady: Z kolei wadą takiej topologi jest możliwość tylko jednej transmisji w danym momencie, dodatkowo awaria kabla powoduje zatrzymanie całej sieci.
  - Zalety: Sporą zaletą topologii magistrali jest fakt, że do budowy sieci używamy krótkich odcinków kabla. Ponadto nie musimy stosować dodatkowych urządzeń takich jak koncentratory czy przełączniki.
  - Gdzie stosowane: Topologia magistrali używana jest w niewielkich sieciach.
  - Źródło informacji: Encyklopedia Zarządzania
- **Topologia pierścienia** (Ring): jest to topologia ktora połącza konkretne elementy i stanowi zamkniętą pętlę, w której każde z urządzeń jest elementem inicjującym i kończącym transmisje danych. W sieci tej dane przekazywane są tylko w jednym kierunku, od jednego urządzenia do kolejnego, do chwili gdy jedno z nich nie okaże się urządzeniem docelowym.
  - Wady: Awaria pojedynczego przewodu lub komputera powoduje unieruchomienie całej sieci, złożona diagnostyka sieci.
  - Zalety: Zaletami tej topologii jest stopień zabezpieczenia przed przeciążeniami i nakładaniem się sygnałów.
  - Gdzie stosowane: W implementacji sieci Token Ring.
  - Źródło informacji: Encyklopedia Zarządzania
- **Topologia gwiazdy** (Star): jest to powszechnie stosowana topologia, zgodnie z założeniami połączenia sieci rozchodzą się gwieździście od węzła centralnego, którym może być koncentrator lub przełącznik. 
  - Wady: Wymagane jest większe zapotrzebowanie na kable oraz konieczność zastosowania koncentratorów.
  - Zalety: Duża przepustowość oraz łatwa lokalizacja uszkodzeń.
  - Gdzie stosowane: Często używane współcześnie z uwagi na swoją elastyczność, skalowalność i niski koszt realizacji.
  - Źródło informacji: Encyklopedia Zarządzania


## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to....
  - Wady: 
  - Zalety: 
  - Zastosowanie: ?
- **Przekazywanie żetonu** (Token Passing): jest to....
  - Wady: 
  - Zalety: 
  - Zastosowanie: ?
- **Wielodostępowa** (Multiple Access): jest to....
  - Wady: 
  - Zalety: 
  - Zastosowanie: ?
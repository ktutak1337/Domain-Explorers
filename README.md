# Domain Explorers

# Spis treści

1. [O repozytorium](#o-repozytorium)
2. [Analiza domeny](#analiza-domeny)  
   2.1 [Czym jest EventStorming?](#czym-jest-eventstorming)  
   2.2 [EventStorming: Big Picture](#eventstorming-big-picture)
   
## O repozytorium

Ten projekt stanowi zapis analizy, modelowania oraz implementacji w ramach [Domain Explorers](https://explorers.bettersoftwaredesign.pl). Znajdziesz tutaj zarówno artefakty wynikowe poszczególnych sesji EventStormingu, modelowania, jak i (docelowo) powstałą na tej bazie implementację.

## Analiza domeny

### Czym jest EventStorming?

Event Storming to metodyka pozwalająca na odkrycie domeny biznesowej, której twórcą jest Alberto Brandolini. Pozwala ona zrozumieć cały proces oraz zidentyfikować problemy, które występują w ramach analizowanej domeny. W proces powinni być zaangażowani interasiarusze związani z daną domeną tacy jak: ekspert domenowy, przedstawiciele biznesu, eksperci techniczni itd. W wyniku warsztatów event stormingu powstają następujące artefakty: Big picture, Process Level oraz Design Level, które są kluczowe w dalszym modelowaniu tworzonego systemu. Pozwalają na wyznacznie kluczowych obszarów domeny, które tak naprawdę przynoszą pieniądze biznesowi, a także domeny poboczne i generyczne, które mają mniejszy wpływ na sukces biznesu, a co za tym idzie nie wymagają aż tak dużej uwagi.

### EventStorming: Big Picture

Celem niniejszych warsztaów było rozpoznanie domeny biznesowej skrzynkomatów.

#### Zamówienie:

![Zamówienie](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-order.png)

#### Baza / sortownia:

![Baza / sortownia](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-warehouse-sorting.png)

#### Załadunek skrzynkomatu:

![Załadunek skrzynkomatu](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-loading.png)

![Załadunek skrzynkomatu 2](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-loading-2.png)

#### Rozaładunek skrzynkomatu:

![Rozaładunek skrzynkomatu](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-unloading.png)

#### Odbiór przesyłki ze skrzynkomatu:

![Odbiór przesyłki ze skrzynkomatu](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-delivery-pickup.png)

#### Reklamacja:

![Reklamacja](https://github.com/ktutak1337/Domain-Explorers/blob/main/assets/big-picture-complaint.png)

Przejdź do [borda](https://miro.com/app/board/o9J_lVEOtSs=/) w aplikacji Miro.

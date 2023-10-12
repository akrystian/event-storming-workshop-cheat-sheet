# EventStorming: Big Picture

## Przygotowanie:

- **Wybór uczestników**: Kluczowe jest zaproszenie osób, które dogłębnie rozumieją proces biznesowy.
- **Definiowanie celu**: Precyzyjne określenie zakresu analizy oraz tego, co pozostaje poza nią.
- **Tworzenie glosariusza**: Aby zapewnić spójność i jasność, warto ustalić i zapisywać kluczowe definicje, kreując wspólny język domenowy.

## Etapy warsztatu:

#### 1. **Wild Exploration**
- Swobodne mapowanie procesu poprzez zdarzenia, bez uwzględnienia ich chronologicznej kolejności.

#### 2. **Enforce Timeline**
- Organizacja zdarzeń w logicznej sekwencji, gdzie:
  - główna ścieżka procesu jest w centrum,
  - eliminowane są powtarzające się elementy,
  - kilka kluczowych zdarzeń może służyć jako punkty orientacyjne w układzie na osi czasu.

#### 3. **Explicit Walk-Through**
- **Przegląd w przód**: Rekonstrukcja "szczęśliwej ścieżki" procesu, weryfikując kompletność modelu.
- **Przegląd w tył**: Analiza procesu od końca do początku, identyfikując zdarzenia prowadzące do kolejnych etapów.

#### 4. **Actors and External Systems**
- Wskazanie aktorów zaangażowanych w proces oraz systemów zewnętrznych wpływających na jego przebieg.

#### 5. **Szanse i ryzyka**
- Analiza procesu pozwala na wskazanie szans i ryzyk związanych z jego obecną postacią.

## Gramatyka:

#### Zdarzenie - pomarańczowa kartka
![zdarzenie](./images/event.png)
- Kluczowa zmiana w analizowanym procesie.
- Opis w formie przeszłej dokonanej.
- Powiązana z konkretnym momentem.
- Dla jasności autorstwa warto oznaczyć karteczkę inicjałami osoby ją dodającej.

#### Hot Spot - różowa kartka
![hot spot](./images/hot_spot.png)
- Wszystkie niejasności, ryzyka i pytania. Zamiast wdawać się w długie dyskusje, warto je odnotować i wrócić do nich później.

#### Aktor - żółta kartka
![aktor](./images/actor.png)

#### System Zewnętrzny - niebieska kartka
![system zewnętrzny](./images/external_system.png)

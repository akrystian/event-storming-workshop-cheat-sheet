# Big Picture EventStorming

## Przygotowanie do warsztatu:
- **Dobór uczestników**: Kluczem do sukcesu jest zaproszenie osób znających proces biznesowy. Wybór właściwych uczestników jest kluczowy.
- **Określenie celu**: Zdefiniowanie zakresu modelowanego procesu oraz tego, co nie wchodzi w jego skład.
- **Tworzenie glosariusza**: Dla spójności i jasności komunikacji warto spisać używane definicje w jednym miejscu, tworząc wspólny język domenowy.

## Etapy warsztatu:
#### 1. **Wild Exploration**
- Mapowanie procesu poprzez zdarzenia bez konieczności zachowania ich chronologicznej kolejności.

#### 2. **Enforce Timeline**
- Organizacja zdarzeń w sposób chronologiczny, gdzie:
  - główna ścieżka procesu znajduje się w części centralnej,
  - usuwane są duplikaty,
  - aby ułatwić układanie, warto wyznaczyć kilka kluczowych zdarzeń i równomiernie je rozmieścić na osi.

#### 3. **Explicit Walk-Through**
- **Przegląd w przód**: Opowieść o "szczęśliwej ścieżce" procesu, umożliwiająca weryfikację kompletności modelu.
- **Przegląd w tył**: Analiza głównej ścieżki procesu od końca do początku, aby zrozumieć, jakie zdarzenia prowadziły do kolejnych.

#### 4. **Actors and External Systems**
- Dodawanie aktorów odpowiedzialnych za konkretną aktywność.
- Wskazanie zewnętrznych systemów mających wpływ na proces.

## Gramatyka:

#### Zdarzenie - pomarańczowa kartka
![zdarzenie](./images/event.png)
- Istotna zmiana stanu w procesie.
- Opisana w formie przeszłej dokonanej.
- Związana z konkretnym momentem czasu.

#### Hot Spot - różowa kartka
![hot spot](./images/hot_spot.png)
- Wszelkie niepewności, ryzyka i pytania. Zamiast długich dyskusji, warto je odłożyć na później.

#### Aktor - żółta kartka
![aktor](./images/actor.png)

#### System Zewnętrzny - niebieska kartka
![system zewnętrzny](./images/external_system.png)

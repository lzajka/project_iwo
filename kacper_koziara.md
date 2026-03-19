# Przypadki użycia - Kacper Koziara

## Diagram Przypadków Użycia

```mermaid
flowchart LR
    A([Organizator]) --> UC1(Zdefiniowanie mapy gry)
    A --> UC2(Zdefiniowanie pomieszczenia)
    A --> UC3(Dodanie postaci/przedmiotu)
    
    UC2 -. "<<extend>>" .-> UC1
    UC3 -. "<<extend>>" .-> UC2

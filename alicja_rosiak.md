```mermaid
flowchart LR

    Gracz --> UCg["Wyświetlenie kalendarza przez gracza"]
    Organizator --> UCo["Wyświetlenie kalendarza przez organizatora"]

    UCg -->|generalization| UC["Wyświetlenie kalendarza"]
    UCo -->|generalization| UC

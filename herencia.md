```mermaid
classDiagram
    note "Vehículos de Transporte"
    Transporte <|-- Guagua
    
    Transporte : +int ruedas
    Transporte : +int asientos
    Transporte: +desplazar()
    Transporte: +informacion()
```

- intercity = Guagua
- lanzaroteBus = Guagua
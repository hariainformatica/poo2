## Apuntes de Programación Orientada a Objetos
https://aprendepython.es/core/modularity/oop/

![Apuntes de POO](https://aprendepython.es/_images/oop.jpg)

### Encapsulación
### Abstracción
### Herencia
### Polimorfismo



## Apuntes de Markdown
https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

### Diagram Class
https://mermaid.js.org/syntax/classDiagram.html

---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
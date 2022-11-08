---

# Company

> I am the sole proprietor of *JohnTelford.com LLC* technology consulting company, working with client  development projects for more that 30 years.

---

## Diagrams

---

### Sequence

``` mermaid
sequenceDiagram
  Alice->>John: Hello John, how are you?
  loop Healthcheck
      John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->>John: Jolly good!
```

---

### Graph

``` mermaid
graph LR
  A[Start] --> B{Error?};
  B -->|Yes| C[Hmm...];
  C --> D[Debug];
  D --> B;
  B ---->|No| E[Yay!];
```

---

### State

``` mermaid
stateDiagram-v2
  state fork_state <<fork>>
    [*] --> fork_state
    fork_state --> State2
    fork_state --> State3

    state join_state <<join>>
    State2 --> join_state
    State3 --> join_state
    join_state --> State4
    State4 --> [*]
```

----

### Class

``` mermaid
classDiagram
  Person <|-- Student
  Person <|-- Professor
  Person : +String name
  Person : +String phoneNumber
  Person : +String emailAddress
  Person: +purchaseParkingPass()
  Address "1" <-- "0..1" Person:lives at
  class Student{
    +int studentNumber
    +int averageMark
    +isEligibleToEnrol()
    +getSeminarsTaken()
  }
  class Professor{
    +int salary
  }
  class Address{
    +String street
    +String city
    +String state
    +int postalCode
    +String country
    -validate()
    +outputAsLabel()  
  }
```

---

### Entity-relationship

``` mermaid
erDiagram
  CUSTOMER ||--o{ ORDER : places
  ORDER ||--|{ LINE-ITEM : contains
  CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

---

## Collaboration

A seasoned, knowledgeable, industry professional, Electronics, Software, and Web Engineer specializing in web hardware and software technology disciplines, Architecture, Architecture, and Deployment.

- Practitioner with extensive experience across most IT functional groups
- Ability to effectively collaborate to accomplish multidiscipline goals:
  - Senior management teams
  - External and internal clients
  - Functional groups
  - Individual contributors
  - Vendors

---


## Nuggets
Way back when the Internet web browsers and programming languages came along, I became interested in web technologies, and began learn by doing technology deep dives. I have years of learning ever changing Electronics, Internet, and Software technologies by hands-on experiencing the technologies du jour.

I have a passion pursuing what’s new and improved with these industries. Checking out what’s new or not, a pipe dream or not, or what’s new and improved, is like panning for gold. Buried within the mountains of info rubble produced daily, every so often one finds interesting technology nuggets making the effort worthwhile. I use the [Hype Curve](http://techtalkjohn.com/hypecurve) as a guide.





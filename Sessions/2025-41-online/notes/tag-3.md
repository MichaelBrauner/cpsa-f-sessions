## Reflexion

Was hätten wir besser machen können. 

- mehr Zeit (halber Tag ist schon heftig knapp)
  - wenn man so schnell ist, muss man die anderen Sachen auch so schnell liefern. 
- abblocken der neuen Anforderung (nicht abnicken)
  - Wir liefern nach - wenn die Zeit dafür gekommen ist.
- Architektur anpassen
  - als die neue Anforderung kam, hätte man die Architektur verbessern müssen
    - Adapter/Provider mit festgelegten Schnittellen (Interfaces)
    - Adapter/Provider mit hoher Kohäsion (diese sollten alle aufgaben diesbezüglich schaffen)
    - Event-System (z.B. register_finished)
- Keycloak (KISS)

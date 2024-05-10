---
title: Lectia 4 - REST API
description: Plan de lecție pentru cursul GoIT
tags:
  - plan
  - lesson
  - learn
---
# Plan de lecție: REST API

## Obiective

La sfârșitul acestei lecții, participanții vor:
- intelege si utiliza variabile de mediu (Environment variables)
- putea folosi pachetul `morgan` pentru logging
- intelege ce reprezinta arhitectura REST
- cunoaste metodele de bază HTTP
- intelege si utiliza CORS
- stii cum sa formeze adresele URL pentru REST API

---

## Desfășurarea lecției

### Raspuns la intrebari + Kahoot

### Prezentarea generală a API-urilor REST
- Ce sunt API-urile REST?
- De ce sunt importante API-urile REST?
- Exemple de API-uri REST populare.
- Beneficiile utilizării Express.js pentru a construi API-uri REST.

### Variabile de mediu 

- Ce sunt variabilele de mediu?
- Cum se definesc variabilele de mediu în diferite sisteme de operare.
- Utilizarea variabilelor de mediu în Express.js:
   - Pachetul `dotenv`
    - Stocarea configurației sensibile în fișierele .env.
    - Accesați variabilele de mediu în codul Express.js.
- Exercițiu: Configurați variabilele de mediu pentru a stoca portul serverului și adresa URL a bazei de date.

### Logging cu Morgan

- Ce este `morgan`?
- Configurarea `morgan` pentru a înregistra solicitările HTTP:
    - Diferite formate de jurnalizare disponibile.
    - Înregistrarea în consolă sau într-un fișier de jurnal.
- Exercițiu: Configurați `morgan` pentru a înregistra solicitările HTTP în consolă.
- Discuție: Importanța logging-ului în aplicațiile web.

### Arhitectura REST

- Principiile fundamentale ale arhitecturii REST:
    - Resurse, reprezentări și metode HTTP.
    - Fără stare, identitate și conectivitate unică.
    - Cacheability și straturi.
- Caracteristicile cheie ale API-urilor REST:
    - Resurse adresabile prin URL.
    - Utilizarea metodelor HTTP pentru a efectua operații CRUD.
    - Reprezentări de date bazate pe JSON sau XML.
- Exercițiu: Identificați resursele, metodele HTTP și reprezentările datelor într-un API REST existent.

### Metode HTTP 

- Semnificația metodelor HTTP comune:
    - GET: Recuperarea datelor.
    - POST: Crearea de resurse noi.
    - PUT: Actualizarea resurselor existente.
    - DELETE: Ștergerea resurselor.
- Asocierea metodelor HTTP cu operații CRUD.

### CORS
- Ce este CORS? (Cross-Origin Resource Sharing)
    - Mecanism de securitate care permite resurselor web de pe un domeniu să fie partajate cu alte domenii.
    - Necesar pentru a permite aplicațiilor web să facă solicitări HTTP către alte domenii (de exemplu, API-uri externe).
- De ce este necesar CORS?
    - Previne atacurile de script cross-site (XSS) și alte vulnerabilități de securitate.
    - Permite o mai bună colaborare între aplicațiile web din diferite domenii.
- Configurarea CORS în Express.js
    - Utilizarea middleware-ului CORS pentru a permite solicitări din diferite domenii.
    - Specificarea originii, metodelor și antetului permise.
    - Exemple de configurare CORS.

### Exercitiu Practic

### Concluzie

- Recapitularea conceptelor cheie:
    - REST, HTTP Methods, Logging, CORS.
- Resurse suplimentare pentru învățare.
- Întrebări și răspunsuri.

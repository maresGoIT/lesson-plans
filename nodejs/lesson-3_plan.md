---
title: Lectia 3 - Introducere in ExpressJS
description: Plan de lecție pentru cursul GoIT
tags:
  - plan
  - lesson
  - learn
---
# Plan de lecție: Introducere în Express.js

## Obiective

* La sfârșitul acestei lecții, participanții vor putea:
    * Defini ce este Express.js și beneficiile utilizării sale.
    * Crea o aplicație Express.js simplă.
    * Utiliza middleware Express.js pentru a extinde funcționalitatea aplicației.
    * Manipula datele primite de la clientul HTTP.
    * Crea rute pentru a gestiona diferite solicitări HTTP.


## Desfășurarea lecției

### Introducere (15 minute)

* Prezentarea Express.js:
    * Ce este Express.js?
    * Beneficiile utilizării Express.js (rapiditate, flexibilitate, ușurință de utilizare).
    * Comparație cu alte framework-uri web Node.js (de exemplu, Koa).
* Demonstrație rapidă:
    * Crearea unei aplicații Express.js simple.
    * Răspunsul la o solicitare HTTP GET de bază.

### Middleware (30 minute)

* Ce este middleware-ul Express.js?
* Tipuri de middleware:
    * Built-in middleware (de exemplu, `express.static`, `express.json`)
    * Middleware personalizat
* Utilizarea middleware-ului pentru:
    * Servirea fișierelor statice (CSS, JavaScript, imagini).
    * ParSarea JSON din solicitările HTTP.
    * Validarea intrărilor utilizatorului.
    * Autentificarea și autorizarea utilizatorilor.
* Demonstrație:
    * Crearea middleware-ului personalizat pentru a saluta un utilizator specific.
    * Utilizarea middleware-ului `express.static` pentru a servi fișiere statice.

### Transferarea datelor către server (30 minute)

* Metode HTTP:
    * GET, POST, PUT, DELETE, etc.
* Utilizarea parametrilor de solicitare pentru a primi date de la client:
    * Parametri din URL.
    * Date din corpul solicitării (JSON, formular).
* Exemple practice:
    * Crearea unui punct final pentru a primi datele formularului.
    * Crearea unui punct final pentru a actualiza o înregistrare în baza de date.

### Rutarea aplicației (30 minute)

* Ce este rutarea Express.js?
* Definirea rutelor pentru a gestiona diferite solicitări HTTP:
    * Rute specifice metodei (GET, POST, etc.).
    * Rute cu parametri dinamici.
    * Rute middleware.
* Exemple practice:
    * Crearea de rute pentru a afișa o listă de utilizatori, a crea un nou utilizator și a edita un utilizator existent.
    * Utilizarea middleware-ului pentru a verifica autentificarea utilizatorului înainte de a accesa anumite rute.

### Concluzie (15 minute)

* Recapitularea conceptelor cheie:
    * Middleware, transfer de date, rutare.
* Resurse suplimentare pentru învățare.
* Întrebări și răspunsuri.

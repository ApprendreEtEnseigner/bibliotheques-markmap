---
title: markmap
markmap:
  colorFreezeLevel: 2
  initialExpandLevel: 1
---

## <i class="fa-solid fa-wand-magic-sparkles"></i> TABLEAU NON CONTRAIN

### 1. DEFINITION

- TYPE-GENERIQUE
- INDICES-LIBRES...
  - PENDANT
  - INSTANCIATION

### 2. STRUCTURE-DONNEES

- TYPE-GENERIQUE...
  - ==Type T_table_reel is array(integer range <>) of float;==
- VARIABLES-CONCRETES...
  - 1.  ==T1: T_table_reel(1..10) → 10 cases==
  - 2.  ==T2: T_table_reel(20..45) → 26 casess==

### 3. IMAGE

- MOULE-EXTENSIBLE...
  - ==<> → gâteaux figés(1..10, 20..45)==

### 4. CAS-PRATIQUES

- DIFFERENCE
  - PACKAGE GTab20.ads
    - ==Type T_tab20 is array(integer range 1..2) of float;==
  - PACKAGE Gestion_tableau.ads
    - ==Type T_table_reel is array(integer range <>) of float;==
  - PACKAGE GTab20.adb
    - ==For i in T'range loop → T'range = 1..2==
  - PACKAGE Gestion_tableau.adb
    - ==For i in T'range loop → T'range = 1..n==

### 5. COMPLEXITE

- ==opérations fondamentales = lectures/assignations sur T(i).==
- ==Saisie = boucle for i in T'range → lit toutes les cases,==
- ==Complexité temps = O(n)==
- ==pire = mieux = moyenne==

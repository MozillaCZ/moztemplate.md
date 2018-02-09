---
revealOptions:
    transition: 'slide'
---
# Template
pro moderní Mozilla slidy
----

## Jednoduchý
a rychlý způsob, jak tvořit slidy v moderním designu. Navržen pro mozilla.cz



---

## Ukázky

Jsou na slajdech níže :)

----

## Obrázky

![San Francisco](sample.png)

----

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

----

### Unordered list:

* Item 1
* Item 2

Ordered list:
1. Item
2. Item

----

### Quotes

Dokážeme taky citace :)

> Nový Firefox je super, a musíte ho používat, protože je super.

---

## Umíme i PDF

<iframe src="pdf.pdf" width="900" height="500"></iframe>

---

## Usage

Jak se template používá najdete níže...

----

### Dependencies

Pro překlad se používá reveal-md

```bash
npm install -g reveal-md
```

Pokud budeme chtít generovat pdf, potřebujeme taky PhantomJS. (Consult your repos).

----

### Použití

Pro zobrazení náhledu stačí spustit

```bash
reveal-md <inputFile>.md
```

_Tip: Použitím přepínače `-w` zapnete live-reload._ 

----

### Použití

Statický export do HTML lze spustit pomocí

```bash
reveal-md <inputFile>.md --static <outputFolder>
```

PDF je možné vygenerovat pomocí

```bash
reveal-md <inputFile>.md --print <outputFile>.pdf
```

----

Své slajdy napíšete v MarkDownu. Jako oddělovač vertikálnách slidů slouží ----,
horizontálních ---.

---

![Panda se zdviženou packou](panda_packa.jpg)
## Otázky?

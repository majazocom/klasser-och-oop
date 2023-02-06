# Klasser och OOP
Övningar inom klasser och OOP inom JS


## Object Literals
```
const home = {
  title: "Villa Villekulla",
  adress: "Bråkmakargatan 11",
  occupants: 1,
  writeInfo: function() {
    return `Det bor ${this.occupants} person i ${this.title} för tillfället`
  }
}
```
1. Kalla på funktionen writeInfo
2. Skriv en till funktion i objektet som skriver ut adressen
3. Kalla på den nya funktionen
4. Skriv ut alla värden på de olika propertys som finns i objektet. Det skall se ut så här efteråt: 
```
["Villa Villekulla", "Bråkmakargatan 11", 1, f, f]
```
5. Skriv ut alla propertys som finns i objektet. Det skall se ut så här efteråt:
```
["title", "adress", "occupants", "writeInfo", "<din nya funktion>"]
```
## Constructor

## Prototypes

## Arv

# Klasser och OOP
Övningar inom klasser och OOP inom JS


## 1. Object Literals
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
6. Skriv din egen version av home-objektet. Med till exempel color, actor, user etc
## 2. Constructor
Exempel på en basic constructor:
```
function Home() {
  console.log('nytt home-objekt skapat')
}

const home = new Home();
```

1. Skriv en ny constructor som tar in 3st parametrar och sparar de som värden i ett nytt objekt. Använd dig av ```this```
2. Skapa din egen version av Home-constructorn nu.

## 3. Prototypes
1. Lägg till (manuellt) en ny property under ```home.prototype``` på din constructor som innehåller en funktion. Så det ser ut som i övning 1.1 med home.writeInfo.
2. Kalla på din nya funktion och se vad som skrivs ut

## 4. Arv

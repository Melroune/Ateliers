Ecrire des fonctions pour: [video]()

Simplement afficher la chaîne “Hello World!”

```
const string = (sentence) => {
  console.log('Hello World!');
  console.log(sentence);
}
string('poulet')
```

Renvoyer à l’ identique le paramètre passé en entrée
```
const same = (para) => {
  return para
}

 const pouet = same('poulet')
 console.log(pouet)
```

Renvoyer le double de la valeur entière passée en entrée

```
const double = number => {
  return number * 2
}

console.log(double(3))
```

Renvoyer l’addition de deux valeurs entières passées en entrée

```
 const add = (a, b) => {
  return a + b
 }
 const poulet = 2
 const yolo = 8
 console.log(add(poulet, yolo))
```

Renvoyer, à partir d’une chaîne de caractères passée en entrée, la même chaîne entourée du caractère * (‘John’ => ‘*John\*’)

```
const starStr = str => {
  console.log("_" + str + "_")
}
const poulet = 'abdou'
starStr(poulet)
```

```
const entourerAvecDesEtoiles = (myString) => {
  let deconstruireMyString = myString.split("")
  deconstruireMyString.push("_")
  deconstruireMyString.unshift("_")
  return deconstruireMyString.join("")
}

const maPhrase = "David Bowie"
console.log(entourerAvecDesEtoiles(maPhrase))
```

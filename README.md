# scotsLang
A programming langauge wi scots syntax; compiles intae javascript. Jist an idea fir noo as ahv no goat the skill tae mak it.

## Syntax

### Variables

```
mak myVariable aye 1 // const myVariable = 1
mak myVariable 2 // let myVariable = 2
```

### Boolean data type
```
mak yes aye // let yes = true
mak no naw // let no = false
```

### Binary logical operators

```
an // &&
or // ||
```

### Relational operators
```
isLessAs // <
isMairAs // >
isLessOrIs // <=
isMairOrIs // >=
```
### Logical assignment operators
```
// &&=
// ||=
```

### Equality operators
```
is // ==
isnae // !=
IS // ===
ISNAE // !==
```

### daeThis ..until
#### scotsLang
```
mak result ''
mak i 0

daeThis
  i += 1
  result += i
until i is 5

cry result // "12345"
```
#### Javascript
```
let result = '';
let i = 0;

do {
  i = i + 1;
  result = result + i;
} while (i < 5);

console.log(result); // "12345"
```

### Functions
#### scotsLang
```
mak myFunction aye (param1, param2)
    gies param1+param2

```
#### Javascript
```
const myFunction = (param1, param2) => {
    return param1+param2;
}
```
```markdown
# Exemplos em JavaScript

## Estrutura if - else if - else

```javascript
if (condition1) {
    // Código a ser executado se condition1 for verdadeira
} else if (condition2) {
    // Código a ser executado se condition2 for verdadeira
} else {
    // Código a ser executado se nenhuma das condições anteriores for verdadeira
}
```

## Estrutura for

```javascript
for (let i = 0; i < limit; i++) {
    // Código a ser repetido enquanto a condição for verdadeira
}
```

## Estrutura while

```javascript
let i = 0;
while (i < limit) {
    // Código a ser repetido enquanto a condição for verdadeira
    i++;
}
```

## Estrutura do while

```javascript
let i = 0;
do {
    // Código a ser repetido pelo menos uma vez, mesmo se a condição for falsa inicialmente
    i++;
} while (i < limit);
```
```javascript
let i = 0;
do {
    console.log(i);
    i++;
} while (i < 5);
```

## Estrutura switch case

```javascript
switch (expression) {
    case 1:
        // Código a ser executado se expression for igual a 1
        break;
    case 2:
        // Código a ser executado se expression for igual a 2
        break;
    default:
        // Código a ser executado se nenhuma das opções anteriores for correspondente
        break;
}
```
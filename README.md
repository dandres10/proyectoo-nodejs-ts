# Operaciones matemáticas Plus

## Instrucciones de instalación:

```
npm install proyectoo-nodejs-ts
```

## Instrucciones de uso

### Importar el módulo
```
En NodeJS
var op = require('proyectoo-nodejs-ts');
En Typescript
import * as matematica from 'proyectoo-nodejs-ts';
```
### Sumas

```
console.log(op.operacion('+', 1,1));
// 2
```

### Restas

```
console.log(op.operacion('-', 1,1));
// 0
```

### Multiplicacion

```
console.log(op.operacion('*', 1,1));
// 1
```

### Division

```
console.log(op.operacion('/', 1,2));
// 0.5
```

### Es par

```
console.log(op.esPar(2));
// true
console.log(op.esPar(251));
// false
```
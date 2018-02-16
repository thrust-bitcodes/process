# Process
Biblioteca que serve de interface para comandos do SO. Funciona como ponte para acesso as APIs do Java.

## Utilização

Instalar o módulo através do comando:

```bash
thrust install process
```

## Exemplo

```js
const process = require('process');


process.exec('ls -lia');
```

## TODO

- [ ] Realizar implementação para Win e Mac

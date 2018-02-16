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

A saída será:

```bash
total 28
1360139 drwxr-xr-x  3 none none 4096 Feb 16 13:07 .
1318678 drwxr-xr-x 63 none none 4096 Feb 16 13:06 ..
1350924 -rw-r--r--  1 none tarcisio  264 Feb 16 13:09 brief.json
1360140 drwxr-xr-x  7 none none 4096 Feb 16 13:10 .git
1350926 -rw-r--r--  1 none none  896 Feb 16 13:09 index.js
1350927 -rw-r--r--  1 none none 1071 Feb 16 13:01 LICENSE
1350928 -rw-r--r--  1 none none  350 Feb 16 13:08 README.md
```

## TODO

- [ ] Realizar implementação para Win e Mac

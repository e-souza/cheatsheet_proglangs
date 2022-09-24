# Shell Script Cheat Sheet

## Variables

Declare:
```sh
varia=1
varia="text $varia"
```

Recover:
```sh
echo $varia
```

## Operators
```sh
```

## Loops

IF:
```sh
test 0 -eq 0 && echo 'true' || echo 'false'
```

```sh
[ 0 -eq 0] && echo 'equal' || echo 'different'
```

```sh
if test -z '' then echo 'void' else echo 'content' fi
```sh
if test -z 'texto'; then echo 'void'; else echo 'content'; fi
```
WHILE:
```sh
while true; do echo 'Hello World'; done
```


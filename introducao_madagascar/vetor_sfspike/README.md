# Aula sobre vetores simples com sfspike e sfdisfil

```sh
sfspike n1=5 k1=2 > a.rsf
sfdisfil < a.rsf
```

```sh
sfspike n1=5 nsp=1 mag=2 | sfdisfil
```

```sh
sfspike n1=10 nsp=2 mag=3,0.5 k1=2,4 | sfdisfil
```

Parâmetros do comando sfdisfil

```
col=2
format="%f " "%.2f"
number=y/n
trailer="eof"
```

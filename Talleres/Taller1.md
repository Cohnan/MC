#Punto 1

Este documento tendrá 2 subsecciones:

1. Una para el código inline y el link, listados en una lista no numerada.
2. Otra para el código en bloque.

##Subsección 1

+ `echo echo Hello, world > hello.txt `
+ [Este es un link con título](https://github.com/Cohnan/MC/tree/master/Talleres "Página de mis talleres")

##Subsección 2

Un codigo en python para calcular la suma de 2 números:

```python
n1 = input()
n2 = input()

print "La suma es", n1 + n2
```

#Punto 2

```bash
#!/bin/bash
# Punto 2 Taller 1 Métodos Computacionales
# 2015-19
# Sebastián Puerto

echo
echo Número, Cuadrado > punto2.csv
for i in {1..1000}
do
	((n = i))
	((m = i*i))
	echo "$n, $m" >> punto2.csv
done
```

#Punto 3

```bash
#!/bin/bash
# Punto 2 Taller 1 Metodos Computacionales
# 2015-19
# Sebastian Puerto

echo
cat punto2.csv | awk 'BEGIN {FS = ","};{print $1 + $2}'
```

#Punto 4

```bash
#!/bin/bash
# Punto 4 Taller 1 Métodos Computacionales
# 2015-19
# Sebastián Puerto

echo
((suma = $1 + $2))
echo "La suma de $1 y $2 es $suma"
echo
```

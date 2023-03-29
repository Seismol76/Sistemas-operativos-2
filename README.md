# Semaforos 

## Concepto
Es una herramienta de sincronizacion que provee el sistema operativo que no requiere 
espera ocupada. Un semaforo(S) es una variable que ademas de la inicializacion,
solo se puede acceder por medio de dos operaciones atomicas y mutuamente exclusivas,
estas son: Wait(S) y Signal(S)

## Semaforos binarios
Estos como su nombre indica solo tienen dos valores, 0 y 1
Este semaforo lo podemos usar por ejemplo para tener solo un proceso o accion a la vez

## Semaforos enteros
Este a diferencia de los binarios pueden almacenar mas valores lo que permite
dar paso a mas acciones para el sistema

## Relacion Sincronizacion con Semaforos

La relacion consiste que los semaforos nos permite sincronizar una
o varias acciones en el sistema para ya sea evitar una sobrecarga o evitar una seccion critica en una parte del codigo
# Sistemas-operativos-2

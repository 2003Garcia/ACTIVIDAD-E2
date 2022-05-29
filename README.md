# Programas de C++ de Garcia Dayana
## Información del autor:
`Autor: Garcia Sanchez Dayana Mariby`

`Correo: dayigarcia2003@gmail.com`

## Programas
...
GarciaDayana-Compara.cpp
GarciaDayana-CuentaMoneda.cpp
GarciaDayana-PuntoVenta.cpp
GarciaDayana-SumaN.cpp
GarciaDayana-laedad.cpp
...

# Descripcion de los programas
### GarciaDayana-Compara.cpp
Este programa en C++ permite comparar dos numeros y determimar si son iguales,o si uno es mayor.
###GarciaDayana-CuentaMoneda.cpp
Este programa en C++ permite determinar la suma de varias monedas y de sus respectivas denomimaciones.
###GarciaDayana-PuntoVenta.cpp
Este programa C++ permite determinar el valor a pagar por la compra de varios productos tomando en cuenta el IVA y su respectivo descuento.
###GarciaDayana-SumaN.cpp
Este programa en C++ permite determinar la suma de varios numeros.
###GarciaDayana-laedad.cpp
Este programa en C++ permite calcular la edad de una persona.
#Funcionalidad
### GarciaDayana-Compara.cpp
```
float Ds_x,Ds_y;
```
#### Salida
```
si(Ds_x==Ds_y) //==> son iguales.
si(Ds_x<Ds_y) //==> y es el mayor,caso contrario x es el mayor.
```
### GarciaDayana-CuentaMoneda.cpp
```
int Ds_n,Ds_c=0,Ds_c1=0,Ds_c2=0,Ds_c3=0;
float Ds_x,Ds_a=0,Ds_a1=0,Ds_a2=0,Ds_a3;
```
#### Salida 
```
Ds_c,Ds_a,Ds_c1,Ds_a1.Ds_c2,Ds_a2,Ds_c3,Ds_a3 //==> Suma total de la moneda,suma de las monedas según su denominación por separados.
```
### GarciaDayana-PuntoVenta.cpp
```
int Ds_C=0,Ds_P;
float Ds_A,Ds_x,Ds_vf,Ds_IVA=0.12,Ds_dsc,Ds_Vb,Ds_Vi,Ds_Vd;
```
#### Salida
```
Ds_Vb,Ds_Vi,Ds_Vd,Ds_vf //==> Valor final a pagar,valor bruto IVA y descuento.
```
### GarciaDayana-SumaN.cpp
``
int Ds_c=0,Ds_V;
float Ds_S,Ds_x;
```
#### Salida
```
Ds_S //==> La suma total de los numeros.
```
### GarciaDayana-laedad.cpp
'''
int Ds_dd,Ds_mm,Ds_yy,Ds_dd1,Ds_mm1,Ds_yy1,Ds_da,Ds_ma,Ds_ya;
```
Ds_ya,Ds_ma,Ds_da //==> Su edad.
```
#Instalación
1.-Descargar F-Droid
```
https://f-droid.org/
```
2.-"Dentro de la aplicación F-Droid".
```
Descargar la terminal (Termux)junto a todas sus actualizaciónes.
```
3.-Ingresar a la terminal (Terux) e instalar los paquetes de datos necearios```
//==> pkg install git
//==> pkg install vim
//==> pkg install clang
//==> pkg install g++
//==> apt upate
//==> apt upgrade
```
```
### Desacargar los repositorios a la terminal (Termux)
1.-Clonar el repositorio en la maquina local.
```
git clone https://github.com/2003Garcia/ACTIVIDAD-E2.git
```
2.-Ingresar al repositorio.
```
cd ~
cd ACTIVIDAD-E2
```
### Compilar y ejecutar.
```
g++ GarciaDayana-SumaN.cpp -o GarciaDayana-SumaN
//==> Asi sucesivamente con los demás programas.
```
```
./GarciaDayana-SumaN
//==> Asi sucesivamente con los demas programas.
```


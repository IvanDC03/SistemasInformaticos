#!/bin/bash

function instalar(){
echo"Introduce un nombre de instalacion: "
}
function ejecutar(){
echo "Introduce si desea ejecutar: "
}
function salir(){
if[$# -eq 0]
echo "salir"
}
function ayuda(){
if[$# -eq 0]
echo "ayuda" 
}
function setColor(){
echo "Introduce un color (RGB)"
if [color==rojo]
echo "Esta bien ese color"
if [color==verde]
echo "Esta bien ese color"
if [color==azul]
echo "Esta bien ese color"
else
echo "Ese color no esta dentro de los colores predeterminados, que son rojo,azul,verde"
}
String funciones = " ";
switch(funciones):
case 1:
echo "¿Que programa quieres instalar?: "
read instalar 
echo ejecutar
read salir
case 2:
echo"¿Necesitas ayuda?"
echo ayuda
echo salir
read salir
case 3:
echo "¿Introduce un color?: "
echo setColor
echo salir 
read salir
default:
echo "Hasta pronto"
read salir
echo "******Menu******"

echo "elije una opción"

echo "opcion 1 instalar"

echo "opcion 2 ayuda"

echo "opcion 3 salir"

read salir

echo "*****Fin Menu*******"

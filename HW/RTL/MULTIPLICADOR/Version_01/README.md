# Multiplicaci�n de n�meros binarios (ejemplo para los  otros grupos)

## Integrantes del equipo de trabajo:

### FERNEY ALBERTO BELTRAN MOLINA  fabeltranm@unal.edu.co

## Descripci�n general del sistema: (tomado del documento de clase)

El algoritmo de multiplicaci�n que se implementa se basa en productos parciales (PP). Se realiza la multiplicaci�n iniciando con el bit menos significativo del multiplicador, el resultado de la multiplicaci�n se suma al primer producto parcial y se obtiene  el segundo producto parcial; si el bit del multiplicador es �0� no se afecta el contenido de PP, por lo que no se realiza la suma. 
A continuaci�n se realiza la multiplicaci�n del siguiente bit (a la izquierda del LSB) y el resultado se suma al producto parcial pero corrido un bit a la izquierda, 
Este proceso continua hasta completar todos los bits del multiplicador y el �ltimo producto parcial es el resultado final. 
## Descripci�n de la caja Funcional  (in/out)
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX

## Descripci�n funcional:
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
## Descripci�n Estructural
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
## Diagrama de Estados
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
## Arquitectura del perif�rico
Se muestra el diagrama de caja funcional para el multiplicador; este m�dulo tiene como  entradas los operandos de 16 bits A y B y la se�al init y como salida el resultado de 32 bits PP y la se�al que indica que ya se realiz� la operaci�n done.

La asignaci�n (puede variar a criterio del dise�ador) dada a estas se�ales; el 
primer operando se encuentra asignado a la direcci�n BASE + 00, donde BASE es  la direcci�n de memoria asignada al perif�rico.

## Diagrama de bloques del perif�rico

Una vez definida la direcci�n de memoria para la informaci�n de entrada y salida del perif�rico
se debe adaptar el dise�o para que permita el intercambio de informaci�n con la CPU. 


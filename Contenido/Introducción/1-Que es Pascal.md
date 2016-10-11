# **Curso de Pascal**

## **Qué es Pascal?**##

Pascal es un Lenguaje de Programación que deriva del lenguaje **ALGOL** e incorpora varias caracteristicas que dieron pie a que su difusión fuera rapida, Pascal es de paradigma imperativo y estructurado, esto quiere decir que es por procedimientos que cambian el estado del programa y que utiliza unicamente las tres siguientes **[estructuras de control](https://es.wikipedia.org/wiki/Estructuras_de_control)**:

1. ##**Secuencia** 

   *Ejemplo:*

   ```pascal
   	(* Sumar Dos Números *)
   	a:= 25 + 10;
   	writeln("Resultado: ", a );
   	(* Resultado: 35 *)
   ```

2. ## **Selección** ( If , Case-Of ) .
   *Ejemplo:*
   ```pascal
      if ( Luz ) then
      	(* Es verdadera la condición *)
      	writeln(" La luz esta encendida ");
      else
      	(* No se cumple la condición *)
      	writeln(" La luz esta apagada ");
   ```

3. ## **Iteración** (bucles for y while, repeat).
   *Ejemplo:*
   ```pascal
      for a := 10  to 20 do
       begin
         writeln('El valor de a es: ', a);
      end;
   ```

# Seudocodigo

##Ordenamiento, Procedimiento
ordenar 12 numeros, de menor a mayor

37 - 15 - 23 - 09 - 00 - 15 - 65 - 13 - 04 - 10 - 11 - 19

37 - 15 - 23 - 09 - 00 - 15 - 65 - 13 - 04 - 10 - 11 - 19
|____|    |____|    |____|    |____|    |____|    |____|
  1         1         0         1         0         0
  
15 - 37 - 09 - 23 - 00 - 15 - 13 - 65 - 04 - 10 - 11 - 19

15 - 37 - 09 - 23 - 00 - 15 - 13 - 65 - 04 - 10 - 11 - 19
     |____|    |____|    |____|    |____|    |____|
       1         1         1         1          0

15 - 09 - 37 - 00 - 23 - 13 - 15 - 04 - 65 - 10 - 11 - 19

15 - 09 - 37 - 00 - 23 - 13 - 15 - 04 - 65 - 10 - 11 - 19
|____|    |____|    |____|    |____|    |____|    |____|
  1         1         1         1         1         0
  
09 - 15 - 00 - 37 - 13 - 23 - 04 - 15 - 10 - 65 - 11 - 19

09 - 15 - 00 - 37 - 13 - 23 - 04 - 15 - 10 - 65 - 11 - 19
     |____|    |____|    |____|    |____|    |____|
       1         1         1         1          1


09 - 00 - 15 - 13 - 37 - 04 - 23 - 10 - 15 - 11 - 65 - 19

09 - 00 - 15 - 13 - 37 - 04 - 23 - 10 - 15 - 11 - 65 - 19
|____|    |____|    |____|    |____|    |____|    |____|
  1         1         1         1         1         1
  
00 - 09 - 13 - 15 - 04 - 37 - 10 - 23 - 11 - 15 - 19 - 65

00 - 09 - 13 - 15 - 04 - 37 - 10 - 23 - 11 - 15 - 19 - 65
     |____|    |____|    |____|    |____|    |____|
       0         1         1         1          0
       
00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65

00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65
|____|    |____|    |____|    |____|    |____|    |____|
  1         1         1         1         1         0
  
00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65

00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65
     |____|    |____|    |____|    |____|    |____|
       0         0         0         0          0
       
00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65

00 - 09 - 13 - 04 - 15 - 10 - 37 - 11 - 23 - 15 - 19 - 65
|____|    |____|    |____|    |____|    |____|    |____|
  0         1         1         1         1         0
  
00 - 09 - 04 - 13 - 10 - 15 - 11 - 37 - 15 - 23 - 19 - 65

00 - 09 - 04 - 13 - 10 - 15 - 11 - 37 - 15 - 23 - 19 - 65
     |____|    |____|    |____|    |____|    |____|
       1         1         1         1         1
       
00 - 04 - 09 - 10 - 13 - 11 - 15 - 15 - 37 - 19 - 23 - 65

00 - 04 - 09 - 10 - 13 - 11 - 15 - 15 - 37 - 19 - 23 - 65  *-*-*-*
|____|    |____|    |____|    |____|    |____|    |____|
  0         0         1         0         1         0
  
00 - 04 - 09 - 10 - 11 - 13 - 15 - 15 - 19 - 37 - 23 - 65

00 - 04 - 09 - 10 - 11 - 13 - 15 - 15 - 19 - 37 - 23 - 65
     |____|    |____|    |____|    |____|    |____|
       0         0         0         0         1

00 - 04 - 09 - 10 - 11 - 13 - 15 - 15 - 19 - 23 - 37 - 65

00 - 04 - 09 - 10 - 11 - 13 - 15 - 15 - 19 - 23 - 37 - 65
|____|    |____|    |____|    |____|    |____|    |____|
  0         0         0         0         0         0
  
00 - 04 - 09 - 10 - 11 - 13 - 15 - 15 - 19 - 23 - 37 - 65
     |____|    |____|    |____|    |____|    |____|
       0         0         0         0         0
       
       Aqui termina por que cuando cumpla en que los dos ultimos son ceros todos, pues termina
Aprendiendo programacion, en este medio del github plasmo como hacer ciertos procediemientos, me gustan los patrones, ahora entiendo su importnacia
darle editar para verlo como lo tenia planeado...

a = 07
b = 15
--------
#>> a = a + b <<
a = 07 + 15
a = 22
#>> b = a - b <<
b = 22 - 15
b = 07
#>> a = a - b <<
a = 22 - 07
a = 15
-------
print(a);
print(b);
_________
a = 15
b = 07
End

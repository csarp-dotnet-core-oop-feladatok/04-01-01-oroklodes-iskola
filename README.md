# 04-01-01-oroklodes-iskola
## Iskola diákjai és tanárai öröklődéssel
A feladata az UML diagramon megadott osztályok kifejlesztése. A feladatban az iskola diákjait és tanárait leíró adatok és metódusok szerepelnek. Mindkét osztálynál található közös vonások, így a feladat megoldását az absztrakt Ember osztály kifejlesztésével kezdje:  
a)  
Egy embernek jellemző tulajdonsága a neve és az életkora  
b)  
Az osztály rendelkezik konstruktorra és az Alszik() és Eszik() metódusokkal. Ezek a metódusok a következő kimenetet adják:  
```
            Diak d = new Diak("Bukfenc Béla", 15, 3.81);
            d.Eszik();
            d.Alszik();
```
A kimenet
```
Bukfenc Béla eszik.
Bukfenc Béla alszik.
```
c)  
A feladatot a Tanár és Diák osztályok kifejlesztésével folytassa. Az UML diagram alapján látszik, hogy ezek az osztályok az Ember osztálytól származnak.
A kódokat úgy fejlessze ki, hogy a következő tesztkódra a megadott kimenetet adja! 
Tesztkód
```
            Diak d = new Diak("Bukfenc Béla", 15, 3.81);
            d.Eszik();
            d.Tanul();
            d.Alszik();
            Tanar t = new Tanar("Jegy János", 32, 22);
            t.Eszik();
            t.Tanit();
            t.Alszik();
```
Kimenet
```
Bukfenc Béla eszik.
Bukfenc Béla tanul és átlaga 3,81.
Bukfenc Béla alszik.
Jegy János eszik.
Jegy János tanít 22 órát.
Jegy János alszik.
```
![image](https://user-images.githubusercontent.com/6060514/116530493-65429300-a8de-11eb-8d8d-1853b3eb33ea.png)

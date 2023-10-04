# Matrix-Accelaration-With-OpenMP-in-C
## THis is my Thesis for the University of Thessaly, in which I'm solving linear algebra's Problems with C and Openmp.

# What is Parallel Programming? 
Before we can ask that, we must consider of how a traditional computer runs a program. A computer runs a piece of code top-down, so every code-line in executed in a serial way.

```C
for(int i=0; i<5; i++){
print(" %d",i);
}
//The result will be >>> 0 1 2 3 4
``` 
The code will run sequentially and the first value will be 0 the second 1 till the end of for loop 4. What will happend if N is greater than 5? Let's say 20 or 20*10<sup>6</sup>. In that case sequential approaches are slow, they will get the job done but slowly. <br><p>Parallel computing or programming are here to save the day. Imagine that you want to paint a room of your house. Imagine that the room has 4 walls that needs to be painted. You can paint those walls yourself but it will take much time less and efford if you take the opportunity and call some friends, "1, 2" as many as you want. Probably is more fun too. :smile:</p>

<p>
</p>






Matrix operations, serial and binary search,

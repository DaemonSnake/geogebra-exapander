# geogebra-exapander
A python3 script for Linux/MinGw that expand all the functions of a Geogebra file in a .c file.</br>
It does so by using the C preprocessor. (it doesn't translate to c, it simply expoits the C preprocessor)</br>
</br>
This script requires cpp (gcc) and python3.</br>
The linux and cpp dependency can be easily replaced with other system specific ones.</br>

The example shipped with this project containts functions that are originals and fall under the same licence as the rest of the program. The MIT licence.

<h2>Why use this ?</h2>
In Geogebra when creating a function composite of other functions it will visualy expand the composition, but visualy only.</br>
<h3>For example :</h3>
f(x) = 2x</br>
g(x) = f(x)²</br>
</br>
<h3>Will show:</h3>
f(x) = 2x</br>
g(x) = 4x²</br>
</br>
The isue here is that this expansion is an image and can't be copied into plain text.</br>
The only way to get this in geogebra is to use the CAS View.</br></br>
But it's not much of a solution as this works only for short/simple expression and is more likely to crash Geogebra more than anything else.

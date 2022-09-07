# Array.

Arrays store data as an ordered collection and each element is assigned an index starting from 0 to n for an array with n elements. Arrays can hold different data types at a time for example the following example is a valid javascript array;

<pre>
<code>
let array = ["one", 2, "three", 4];
</code>
</pre>

In javascript arrays are primitive and contain the following characteristics;

> Arrays start from the index zero and the index of the last element is the lenght (total elements in an array) minus 1.
>
> Javascript arrays are resizable (elemnts can be added and removed) and can contain a mixture of different data types. For using a single data type in an array, you can opt to use **Typed Arrays**
>
> Javascript arrays are not associative arrays therefore array elements cannot be accessed using arbitrary strings but are accessed using the element's index.
> Javascript array-copy-operations create shallow copies.

In javascript `Array()` constructor is used to create new `Array` objects for example;

<pre>
<code>
/* Array() constructor syntax */

Array("index0", "index1", /* ... */ "index2");

/* Example 1 */

const students = Array(5);
console.log(students.length); //5
</code>
</pre>

Arrays can also be constructed using the literal notation, an example of constructing the array using the literal notation is;

<pre>
<code>
/* literal notation syntax */
const exampleArray = ["element0", "element1", /* ... */ "elementN"];

/* example */

const cars = ["Bus", "lorry", "Van", "Truck"];
console.log(cars) //[ 'Bus', 'lorry', 'Van', 'Truck' ]
</code>
</pre>

#### Typed Arrays

In javascript typed arrays are array-like objects that provide a mechanism for raeding and writing raw binary data in the memory buffers.

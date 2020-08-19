# Common Collections
* Rust’s standard library includes a number of very useful data structures called collections.
* Most other data types represent one specific value, but collections can contain multiple values.
* Unlike the built-in array and tuple types.
* the data these collections point to is stored on the heap, which means the amount of data does not need to be known at compile time and can grow or shrink as the
program runs.
* 

## Storing Lists of Values with ``Vectors``
* The first collection type we’ll look at is ``Vec<T>``, also known as a vector. 
* Vectors allow you to store more than one value in a single data structure that puts all the values next to each other in memory.
* Vectors can only store values of the same type.
* They are useful when you have a list of items, such as the lines of text in a file or the prices of items in a shopping cart.
## Storing UTF-8 Encoded Text with ``Strings``
## Storing Keys with Associated Values in ``HashMaps``
* The type HashMap<K, V> stores a mapping of keys of type K to values of type V.
* It does this via a hashing function, which determines how it places these keys and values into memory.
* Many programming languages support this kind of data structure, but they often use a different name, such as hash, map, object, hash table, dictionary, or associative array, just to name a few.
* Hash maps are useful when you want to look up data not by using an index, as you can with vectors, but by using a key that can be of any type. 
* For example, in a game, you could keep track of each team’s score in a hash map in which each key is a team’s name and the values are each team’s score. Given a team name, you can retrieve its score.
* hash maps store their data on the heap. This HashMap has keys of type String and values of type i32.
* hash maps are homogeneous: all of the keys must have the same type, and all of the values must have the same type.

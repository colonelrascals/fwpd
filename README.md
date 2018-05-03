# fwpd

Consuming a CSV



## Function Explanation

**vamp-keys**: Vector of keys used to create vampire map

**str->int**: Converts string to integer

**conversions**: associates conversion function to each vamp-keys. 

**convert**: takes vamp-key and value and returns converted value

**parse**: takes a string and spilts it on the newline to create a seq of strings. Maps over the seq of strings spiltting at the comma character.

**mapify**: takes the seq of vectors and combines with vamp-keys to create maps.

**glitter-filter**: filters out those with an index less than 3.

## License

Copyright © 2018 FIXME

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.

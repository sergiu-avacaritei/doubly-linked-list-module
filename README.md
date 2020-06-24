# DOUBLY LINKED LIST MODULE
This is a library module supporting lists. A list stores any number of items
and has a current item, which can be any item from the first item to the
last item or a unique 'none' position indicating
that no item is selected. Every operation is constant time.
The items stored in a list are of type 'item'. The typedef for this can be
changed for any particular application so that 'item' stands for any desired
type, e.g. a raw type such as int, double, ...
A typical forward traversal has the form:

```sh
  first(l);
  while (after(l)) {
    item x = get(l); ...
  }
 ```
 
Note that all key functions are symmetrical with respect
to traversal direction or have matching counterparts.
The lists provided by this module are not thread safe. 

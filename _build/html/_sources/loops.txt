==================
Loops
==================

Opening words
++++++++++++++++++

Loops in python and go are very similar. In Python we have both while loops and for loops,
but in go we only have for loops. For loops in go are very similar to while loops in python.
The range keyword also makes go's for loops quite similar to pythons for loops.


Examples
++++++++++++++++++

Loop forever in Python::

    while True:
        print("Looping")

Loop forever in Go::

    for {
        fmt.Println("Looping")
    }

Iterate over list in Python::

    for element in mylist:
        print(element)

Iterate over slice in Go::

   for _, element := range myslice {
        fmt.Println("element")
    }

Count to ten in Python::

    for i in range(11):
        print(i)

Count to ten in Go::

    for i:=0; i < 11; i++ {
        fmt.Println(i)
    }

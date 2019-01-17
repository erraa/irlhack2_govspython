==================
Lists and Dicts
==================

We don't have lists or dicts in go, we have arrays (slices) and maps

Lists vs Arrays
++++++++++++++++++

Python::

    mylist = [1,2,3]

Golang::

    mylist := []int{1,2,3}

Dicts vs Maps
+++++++++++++++++++

Python::

    mydict = {"one": 1}
    mydict["two"] = 2

Golang::

    mydict := map[string]int{"one":1}
    mydict["two"] = 2

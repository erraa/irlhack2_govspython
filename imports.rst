==================
Imports and Pip vs Go get
==================

Imports in Go and Python are very similar, but go really encourages an imformative way of importing.

**Python**

Pip3 install::

    pip3 install requests

importing::

    import requests
    import json

**Golang**

go get::

   go get github.com/gorilla/mux

importing::

    import (
        "fmt"
        "github.com/gorilla/mux"
    )

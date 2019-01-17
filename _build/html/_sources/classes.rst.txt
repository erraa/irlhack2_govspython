==================
Classes Vs Structs
==================


Golang::

    type Twitter struct {
        username string
        password string
    }

    func (t *twitter) login() {
        somecode
    }

Python::

    class Twitter(object):
        def __init__(self, username, password):
            self.username = username
            self.password = password

    def login(self):
        pass


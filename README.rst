NAME

::

   objects - clean namespace


DESCRIPTION


::

    objects provides an Object class and a seperate out of methods
    into functions that take Objects as the first argument.


    objects is intended to be programmable  in a static, only code, 
    no popen, no user imports and no reading modules from a directory,
    way. 


INSTALL


::

    $ pip install objects


USAGE


::

    >>> from objects import Object, read, write
    >>> o = Object()
    >>> o.a = "b"
    >>> pth = write(o)
    >>> oo = Object()
    >>> read(oo, pth)
    

AUTHOR

::

    Bart Thate <programmingobject@gmail.com>


COPYRIGHT

::

    objects is placed in the public domain.

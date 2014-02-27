Namedtuples, without code templates!
==================================

A subclass of tuple that allows for named attribute access. Note that a structure with the same name and usage is available in Python 2.6 as collections.namedtuple, but this is smaller and available in Python 2.4+. If you ask the question "should I use this or collections.namedtuple?" the answer will invariably be the latter. The only real benefit this offers is that it is implemented in pure Python and does not generate any code, whereas the Python-sanctioned version has a Python code template string it customizes and runs eval() on. If that makes you nervous/angry, this is your alternative.

License
-------
I release this into the public domain.

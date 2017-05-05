Remind - Pascha
===============

This is a function for [remind](https://www.roaringpenguin.com/products/remind) to compute the date of Pascha (Christian Orthodox Easter).
Remind comes with a function for western Easter built in, but not one for Pascha,
so this adds it.

There are two files:

- `pascha_lib.rem`: This defines the function `_paschadate`.
   It takes one argument.
   If you give it a year (an int), it will tell you the date of Pascha in that year.
   If you give it a date, it will tell you the first date of Pascha after that date.
   It has three algorithms, Metonic, Gauss, and Meeus.
   You can choose the one you want by setting a constant in the file.

- `pascha.rem`: This uses `_paschadate` to set a trigger for Pascha and other dates on the Paschal cycle.

Author
------

Paul A. Jungwirth <pj@illuminatedcomputing.com>

License
-------

MIT



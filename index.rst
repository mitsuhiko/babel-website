public: yes

Welcome
=======

    Babel is an internationalization library for Python.  It has full
    unicode support and provides access to the CLDR data files.
    It's widely used and BSD licensed.

Babel is Simple and Useful
--------------------------

::

    >>> from babel.dates import format_datetime
    >>> print format_datetime(locale='ru_RU')
    26 июля 2013 г., 15:48:18

    >>> from babel.numbers import format_currency
    >>> print format_currency(10.50, 'EUR', locale='de_DE')
    10,50 €
    >>> print format_currency(10.50, 'USD', locale='en_AU')
    US$10.50


And Powerful
------------

Babel provides access to the majority of the CLDR data.  It simplifies
internationalization by doing the heavy lifting for you.  It can format
dates, timespans and all kinds of number information.  It simplifies
dealing with timezones and gives you access to the raw data (like month
and timezone names, how formatting works for different languages and
more).

Wide Range of Features
----------------------

-   Extensible string extraction and merging support for
    internationalization.
-   Catalog management tools (merging, updating etc.)
-   Support for reading and writing PO and MO files.
-   Convenient access to CLDR data.
-   date, time and timedelta formatting
-   Timezone support through pytz
-   System local timezone support
-   Number and currency formatting
-   Pluralization support


Contribute
----------

Found a bug? Have a good idea for improving Babel? Head over to
`Babel's new github <http://github.com/mitsuhiko/babel>`_ page and
create a new ticket or fork.  If you just want to chat with fellow
developers, visit the `IRC channel </community/#irc-channel>`_ or join the
`mailinglist </community/#mailinglist>`_. 

.. raw:: html

    <a href="http://github.com/mitsuhiko/babel"><img style="position: fixed; top: 0; right: 0; border: 0;"
       src="http://s3.amazonaws.com/github/ribbons/forkme_right_gray_6d6d6d.png" alt="Fork me on GitHub"></a>

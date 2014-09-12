dogefetch
=========

A dogecoin price fetcher written in python (all output is in USD).

Using dogefetch
---------------

dogefetch takes one argument from the command line:

'wow' fetches the price of DOGE.

'l' fetches the price of LTC.

'b' fetches the price of BTC.

'all' fetches the prices of LTC, BTC and DOGE.

It is possible to fetch two values. For example, lwow will return the prices of both
LTC and DOGE.

Example: <code>$ dogefetch bl</code>

Resolving Dependencies
----------------------
This script requires python3 and python3-requests.

Python3 can be installed through your distrubution's package manager, or downloaded from 
[python's website](https://www.python.org/).

Python3-requests can be easily installed through pip:

<code>$ pip install requests</code>

Python3-requests also have installation instructions on their 
[website](http://docs.python-requests.org/en/latest/user/install/#install).

Installation
------------

To install dogefetch:

<code>$ chmod +x ./dogefetch && sudo cp ./dogefetch /usr/local/bin/</code>

Licensing
---------

This script is [free software](http://gnu.org/philosophy/free-sw.html), licensed
under the terms of the MIT license. See [LICENSE](LICENSE) for more information.

Donating
---------

Any donations will be gratefully recieved:

DOGE: DJepsAo6xM5LY6HosM6mFB6EDDaJ9BvasC

BTC:  1BY5hrgvAJAmKzFHbuCgNUucg231iyBW4C

LTC:  LLLtdzMJg5ZqFDz1ncyyVnMizvCbzFNfAk

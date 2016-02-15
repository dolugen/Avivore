#Avivore
###The Twitter-searching Data Miner

Avivore is a Python-based tool that searches Twitter for keywords and then parses any tweets that are
found. When parsing, it looks for the following sort of data:

* Phone numbers in NPA-NXX format (ex: 604-555-1212)
* IPv4 addresses (127.0.0.1)
* Blackberry PINs (ABCDEF12)

It presently uses a SQLite backend to store the data that is found and outputs results via a Console. It 
has only been tested on Ubuntu Linux but there should be no real reason for it not to work under OS X, 
Windows, or any other platform capable of running Python.

I am certainly open to new data sets that it could pull. E-mail addresses were considered but at the time 
that I was writing all of this, I was not as interested in that information.

This tool is intended to be used for demonstration purposes and has some of my more extensive keyword 
searches removed. It was first presented at BSides Vancouver on March 4th, 2013.

###Requirements
* Python 3
* SQLite and Twitter modules (pip install twitter)

No Twitter account is required for access.

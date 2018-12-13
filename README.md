RegSvrEx
========

Overview
--------

This is a tiny tool capable of registering Windows COM DLLs (and EXEs in 32 bit
version) for the current user only, something that is inexplicably not
supported by the standard `regsvr32.exe` tool included in Windows itself.

See the [original article](http://www.codeproject.com/Articles/3505/RegSvrEx-An-Enchanced-COM-Server-Registration-Util)
for more information.


Instructions
------------

Get the sources and build them using MSVS 2017 (earlier versions can probably
be used as well, but the project files in the repository requires this one) or
just grab the
[binary](https://github.com/vadz/RegSvrEx/releases/download/v1.0.0.1/RegSvrEx.exe)
as this is normally all you need.


Credits
-------

The program was written by [Rama Krishna Vavilala](http://www.codeproject.com/script/Membership/View.aspx?mid=15383)
and I (Vadim Zeitlin) have only built it in 64 bits.

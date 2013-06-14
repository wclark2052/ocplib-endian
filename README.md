ocplib-endian
=============

Optimised functions to read and write int16/32/64 from strings and
bigarrays, based on new primitives added in version 4.01.

The library implements two modules:
- [EndianString](src/endianString.mli) works directly on strings, and provides submodules BigEndian and LittleEndian, with their unsafe counter-parts;
- [EndianBigstring](src/endianBigstring.mli) works on bigstrings (Bigarrays of chars), and provides submodules BigEndian and LittleEndian, with their unsafe counter-parts;


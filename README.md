Polymorphic viruses source sample
========
**IF YOU HAVE NO IDEA WHY ARE YOU HERE THEN LEAVE NOW**
Features
--------
- infects PE files (DLL/EXE);
- does not change section attributes of the file infected;
- stores the first polymorphic decryptor in the first executed section;
- expands the last section and stores useful load there, as well as stolen data and additional information; all that is stored encrypted and with different keys;
- applies the Extended EPO method to transfer control to the first decryptor;
- the second decryptor is built by the "Infernal trash" method aimed at complicating the treatment;
- written in C with ASM inlines;
- every infected file will contain useful load.
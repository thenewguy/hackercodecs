Hacker Codecs
=============

This is a set of codecs for decoding and encoing things related to
hacking and hacking CTFs. Specifically this was designed originally
around the fact that decode('bin') doesn't exist in the standard
library and there are times (especially in a CTF) where this is
extremely convinient.

Later 'morse' was added to easily encode and decode morse code without
needing to do it (as) manually. 

The 'ascii85' codec was added specifically for PDF parsing in
forensics challenges. This could be used, for example, with
python-magic to check if a string inside of a PDF is actually a file
of a specific type. 

The 'url' and 'entity' codecs were added as a quick way to encode and
decode data for web hacking. 

'y' is a stripped down 'yenc' as used for NNTP. Headers and footers
are not included, they will need to be handled elsewhere. 

Other encodings may have been added, a full list is avaliable by reviewing the code. 

As I run across, or am told about other obscure encoding methods I
will continue to add to this library. 


Copying
-------

Copyright © 2012–2015 Josh Dukes <hex@neg9.org> and contributors.

This is free software: you may copy, modify, and/or distribute this work
under the terms of the Expat License.
No warranty expressed or implied. See the file ‘LICENSE.Expat’ for details.


[comment]: # Local variables:
[comment]: # coding: utf-8
[comment]: # mode: text
[comment]: # mode: markdown
[comment]: # End:
[comment]: # vim: fileencoding=utf-8 filetype=markdown :


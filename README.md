git-magic-epub
==============

I wanted to read the Git Magic book in Google Books, so I tried to figure how to turn it into a nice epub file.

I converted the [single html file version](http://www-cs-students.stanford.edu/~blynn/gitmagic/book.html), using [pandoc](http://johnmacfarlane.net/pandoc/index.html) to do the conversion. The original book appears to be in AsciiDoc, which I'm not familiar with, but probably you could set it up and do a more clean/direct conversion to epub that way.

After conversion, I edited the file in [Sigil EPUB Editor](https://code.google.com/p/sigil/), in order to segment the chapters, to clean the table of contents and add the metadata. It should work well in any epub reader (though I have only tried Google Books). I made my own minimalistic cover too, but you could easily change this if you want.

Download
---------

Download the [gitmagic](/gitmagic.epub) file above.

Sources
---------

Original files can be found here:

http://www-cs-students.stanford.edu/~blynn/gitmagic/

https://github.com/blynn/gitmagic

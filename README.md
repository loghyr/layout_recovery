This draft describes an extension to the NFSv42 protocol.

In particular, it extends the use of a special stateid in LAYOUTRETURN
to allow the client to report errors during recovery.

http://www.ietf.org/html.charters/nfsv4-charter.html
http://www.ietf.org/mail-archive/web/nfsv4/index.html

NOTE: The drafts contained here may change after it is
posted to the IETF site. The ITEF site is always the
definitive authority on content.

You can easily install xml2rfc to get the tools
necessary to make the text file version:

   > pip install xml2rfc

Notes to build:

1. Bump the VERS in Makefile

2. Build

   > make

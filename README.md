journalarchiver
===============

Prototype for trickle feed of journal archive

Proof of concept to get methods and xpaths right for the retrieval of journal content
(vols, issues, articles, graphics, pdfs etc) from the HighWire API.

Also first attempt with git

Basic principle is to do an API search e.g. (for last seven days); get an Atom XMl file returned; trawl through this to build an annotated list of relevant urls for retrieval of items (some urls returned imply further subsets of urls need to be retrieved); use the list of urls to get and store items onto local network

This will be mainly ANT, XPATH, XSLT

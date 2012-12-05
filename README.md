erlang-pbkdf2
=============

A [PBKDF2][] implementation for [Erlang][] extracted from [Apache CouchDB][].

[PBKDF2]: http://en.wikipedia.org/wiki/PBKDF2
[Erlang]: http://www.erlang.org
[Apache CouchDB]: http://couchdb.apache.org


Building
--------

`erlang-pbkdf2` uses [rebar][] to manage the build process. To build the project, run:

	./rebar compile

You can then run the `xref` and `eunit` tests:

	./rebar xref eunit

If you want to remove all generated files, run:

	./rebar clean

[rebar]: https://github.com/rebar/rebar/wiki


Cryptographic Software Notice
-----------------------------

This distribution includes cryptographic software. The country in which you
currently reside may have restrictions on the import, possession, use, and/or
re-export to another country, of encryption software. BEFORE using any
encryption software, please check your country's laws, regulations and policies
concerning the import, possession, or use, and re-export of encryption software,
to see if this is permitted. See <http://www.wassenaar.org/> for more
information.

The U.S. Government Department of Commerce, Bureau of Industry and Security
(BIS), has classified this software as Export Commodity Control Number (ECCN)
5D002.C.1, which includes information security software using or performing
cryptographic functions with asymmetric algorithms. The form and manner of this
Apache Software Foundation distribution makes it eligible for export under the
License Exception ENC Technology Software Unrestricted (TSU) exception (see the
BIS Export Administration Regulations, Section 740.13) for both object code and
source code.

The following provides more details on the included cryptographic software:

`erlang-pbkdf2` implements the PBKDF2 key derivation function.
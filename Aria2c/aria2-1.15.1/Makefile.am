SUBDIRS =  po intl lib deps src doc test

ACLOCAL_AMFLAGS = -I m4 --install

EXTRA_DIST = config.rpath

dist_doc_DATA = README README.rst README.html

dist_noinst_DATA = LICENSE.OpenSSL

README.html: README.rst
	rst2html README.rst > README.html

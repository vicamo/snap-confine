dist_man_MANS = snap-confine.5 snap-discard-ns.5 ubuntu-core-launcher.1

CLEANFILES = snap-confine.5 snap-discard-ns.5 ubuntu-core-launcher.1
EXTRA_DIST = snap-confine.rst snap-discard-ns.rst ubuntu-core-launcher.rst

%.5: %.rst
	rst2man $^ > $@

ubuntu-core-launcher.1: ubuntu-core-launcher.rst
	rst2man $^ > $@

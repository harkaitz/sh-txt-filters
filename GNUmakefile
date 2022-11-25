DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	@mkdir -p $(DESTDIR)$(PREFIX)/bin
	@echo 'I bin/txt-unwrap'; cp bin/txt-unwrap  $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	@echo 'I share/doc/sh-txt-filters/LICENSE'
	@mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-txt-filters
	@cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-txt-filters
## -- license --

.PHONY: FORCE
all: FORCE
	$(MAKE) -C .. darkcoin_qt test_darkcoin_qt
clean: FORCE
	$(MAKE) -C .. darkcoin_qt_clean test_darkcoin_qt_clean
check: FORCE
	$(MAKE) -C .. test_darkcoin_qt_check
darkcoin-qt darkcoin-qt.exe: FORCE
	 $(MAKE) -C .. darkcoin_qt

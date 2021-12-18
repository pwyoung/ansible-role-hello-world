.PHONY=build clean FORCE

MAKEFILE_PATH=$(dir $(realpath $(firstword $(MAKEFILE_LIST))))

build: FORCE
	$(info Build make)
	@nomaj

clean: FORCE
	$(info Clean make)
	@nomaj -x clean
	$(info Removing build dir)
	rm -rf $(MAKEFILE_PATH)build

FORCE:

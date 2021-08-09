AS=asm -v -n -C 6805

%.S19:	%.ASM
	$(AS) -l $*.LST -o $@ $^

.PHONY: clean distclean

all: ASSIST05.S19

clean:
	-rm -f *.LST
distclean: clean
	-rm -f *.S19

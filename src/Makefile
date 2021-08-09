AS=asm -C 6805 -n -u

%.S19:	%.ASM
	$(AS) -l $*.LST -o $@ $^

.PHONY: clean

all: ASSIST05.S19

clean:
	-rm -f *.p *.lst *.LST *.S19

all: uf2conv.exe

uf2conv.exe: uf2conv.c
	gcc -DSAMD21 -static -fno-diagnostics-color -I../inc -o uf2conv.exe uf2conv.c

.PHONY:

clean:
	rm -f uf2conv.exe


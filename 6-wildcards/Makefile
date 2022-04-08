files := one.c two.c

all: one.c two.c print

one.c two.c:
	touch $@

print: $(wildcard *.c)
	ls -la  $?

clean:
	rm -f ${files}


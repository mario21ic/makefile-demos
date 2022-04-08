files := one two

all: one two

one two:
	touch $@

# Equivalent to
#one:
#	touch one
#two:
#	touch two

clean:
	rm -f ${files}


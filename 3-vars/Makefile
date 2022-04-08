files := file1 file2
file2 := another_file
some_file: $(files)
	echo "Look at this variable: " $(files)
	touch some_file
	touch $(file2)

file1:
	touch file1
file2:
	touch file2

clean:
	rm -f file1 file2 some_file $(file2)


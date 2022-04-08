files := file1 file2
file2 := another_file

some_file: $(files)
	echo "Look at this variable: " $(files)
	touch $(file2)
	touch some_file

file1:
	touch file1
file2:
	touch file2

clean:
	rm -f ${files} some_file ${file2}


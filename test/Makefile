
livre.txt: section-1.txt section-2.txt
	cat section-1.txt section-2.txt > livre.txt

section-1.txt: chapitre-1-1.txt chapitre-1-2.txt
	cat chapitre-1-1.txt chapitre-1-2.txt > section-1.txt

section-2.txt: chapitre-2-1.txt chapitre-2-2.txt
	cat chapitre-2-1.txt chapitre-2-2.txt > section-2.txt

clean:
	rm section-1.txt section-2.txt livre.txt

error-test:
	echo "Next command will fail"
	false
	echo "The will be run with '-k'"

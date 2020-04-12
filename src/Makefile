default:	aggregated/checkers.txt

aggregated/checkers.txt:	divided/*
	rm -f aggregated/checkers.txt
	for file in divided/* ; do cat "$$file" >> aggregated/checkers.txt ; done

clean:
	rm -f aggregated/checkers.txt

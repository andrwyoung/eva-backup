# NAME: Andrew Yong
# EMAIL: yong.andrew11@gmail.com
# ID: 604905807

files = simpsh.c printers.c commander.c filers.c utils.c signals.c profiler.c
heads = printers.h commander.h filers.h utils.h signals.h profiler.h
tars = Makefile checker.sh README
id = 604905807
name = simpsh

$(name): $(files) $(heads)
	gcc -o $(name) $(files)

.PHONY: clean
clean:
	-@rm simpsh lab1-$(id).tar.gz

.PHONY: dist
dist:
	tar -czf lab1-$(id).tar.gz $(files) $(tars) $(heads) report.pdf

.PHONY: check
check:
	chmod +x checker.sh
	./checker.sh



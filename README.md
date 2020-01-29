# pa1-peddiashrith
### Makefile contains following targets:
1. team
	1. prints our team and team member names
2. compiler	
	1. lex lex.l where lex.l is file in which instructions are wrote
	2. gcc lex.yy.c which compiles file generated which by above line
	3. ./a.out which is a executable file. When it starts executing it asks for input filename (eg: loop.micro or sqrt.micro which should be entered in terminal) from which it reads the file
3. clean
	1. which removes intermediate files

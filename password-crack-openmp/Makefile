CC=gcc
CCMAC=clang

password-crack: password-crack.c sha-256.c
	$(CC) -fopenmp -o password-crack.exe password-crack.c sha-256.c

password-crack-soln: password-crack-soln.c sha-256.c
	$(CC) -fopenmp -o password-crack-soln.exe password-crack-soln.c sha-256.c

password-crack-mac: password-crack.c sha-256.c
	$(CCMAC) -Xpreprocessor -fopenmp -o password-crack password-crack.c sha-256.c
	
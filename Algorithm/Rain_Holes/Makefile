
all:
	rm -rf *.ra
	cat  header_rain.h > backup.ra
	cat *.c >> backup.ra
	time gcc -static *.c -o rainHoles
clean:
	rm -rf rainHoles *.ra *.md

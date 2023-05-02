blah: blah.o
	cc blah.c -o blah # Runs third

blah.o: blah.c
	cc blah.c -o blah.o # Runs second

# Typically blah.c would already exist, but I want to limit any additional required files
blah.c:
	echo "int main() { return 10; }" > blah.c # Runs first

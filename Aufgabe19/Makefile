CC=gcc
CFLAGS="-Wall"
GPROF="-gp"
RM="rm"

DEPS = 
OBJ = leapYear_error.o 

%.o: %.c $(DEPS)
	$(CC) -c -o  $@ $< $(CFLAGS) -g
leapYear_error: $(OBJ)
	$(CC) -o  $@ $^ $(CFLAGS) -g 
debug:$(OBJ)
	$(CC) -o  $@ $^ $(CFLAGS) -g
clean:
	$(RM) *leapYear_error *.o
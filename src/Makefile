objects = main.o
headers = 
binary = ippc

$(binary): $(objects) 
	g++ -o $@ $(objects)

$(objects): $(headers)

.PHONY: clean
clean:
	rm -f $(objects) $(binary)


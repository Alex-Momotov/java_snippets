#.DEFAULT_GOAL := say_goodbye
all: say_hello generate say_goodbye

say_hello:
	@ echo "hello"

generate:
	@ echo "generating some files"
	@ touch {1..9}.txt

say_goodbye:
	@ echo "goodbye"

make clean:
	rm ./*.txt

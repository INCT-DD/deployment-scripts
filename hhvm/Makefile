SOURCE	 = install_hhvm.pow
OUT	     = install_hhvm.sh
POW	     = powscript
FLAGS	 = --compile --to bash --no-cache


all:
	$(POW) $(FLAGS) $(SOURCE) -o $(OUT)
	chmod +x $(OUT)

clean:
	rm -f $(OUT)
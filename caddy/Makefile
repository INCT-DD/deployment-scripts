SOURCE	 = install_caddy.pow
OUT	     = install_caddy.sh
POW	     = powscript
FLAGS	 = --compile --to bash --no-cache


all:
	$(POW) $(FLAGS) $(SOURCE) -o $(OUT)
	chmod +x $(OUT)

clean:
	rm -f $(OUT)
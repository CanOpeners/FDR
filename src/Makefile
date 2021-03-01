RUBBER = rubber
MAIN = main

.PHONY: all clean serve full

full:
	@make clean && make all; make all; make compress

all:
	$(RUBBER) --pdf $(MAIN).tex

clean:
	$(RUBBER) --clean $(MAIN).tex
	@if [ -f "main.sta" ] ; then rm main.sta; fi
serve:
	@while true; do inotifywait $(MAIN).tex; sleep 1; make all; done

compress: all
	ps2pdf "$(MAIN).pdf" "$(MAIN).min.pdf"

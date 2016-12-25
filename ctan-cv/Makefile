# variables
CV = cv.tex
RESUME = resume.tex
COMPILE = latexmk
RM = rm -rf

# rules
.PHONY : all clean

mycv : 
	$(COMPILE) $(CV)
myresume : 
	$(COMPILE) $(RESUME)
clean :
	$(COMPILE) -C
	@$(RM) auto/ cv/auto/ resume/auto

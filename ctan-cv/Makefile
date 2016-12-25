# variables
CV = cv
RESUME = resume
COMPILE = latexmk
RM = rm -rf

# rules
.PHONY : all clean

all : cv, resume

cv : 
	$(COMPILE) $(CV)
resume : 
	$(COMPILE) $(RESUME)
clean :
	$(COMPILE) -C
	@$(RM) auto/ cv/auto/ resume/auto

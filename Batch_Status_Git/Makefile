# Goes through all listed directories and prints out their 'git status'
DIRECTORIES = one_directory another_directory yet_another

DIV = "======================================================"

status :
	@$(foreach dir,$(DIRECTORIES),printf "\n$(DIV)"; printf "\nChecking "; printf "$(dir)...\n"; cd $(dir); git status; cd ..;)

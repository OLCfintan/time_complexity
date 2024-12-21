   -This program is created with -C-

-->1


	creat a program that count time complexity of a program

	structure :

		-count total of best worst and average cases
		-implement functions that know the type of time incrementation 
			for exp[factorial exponential logaritmique ...]
		-creat or search for tool to know the specifique value of unit of time
		-2 functions :
			1-->for check with while and for
			2-->for check with 1 and if the termination of a function is correct
		-for the moment just a few types of files
		

-->2


	[linked list]::>

		-t_lexer *lexer  :
 					....
		-time_notation_t :
				-loop_t *loops[linked_list] : number of loops //for knowing if i have loops inside loops and know the exact order
					  [int number of while] [int number of for] [int if_inside_loop] [next]
				-int total 		    : total time of the function
				-char *type_of_inrementations // for knowing the type of inrementations inside the function;
				-int if_infini;
				-time_notaion_t *next //for next function

	[functions]:::>

		-char 		*get_next_line 		 : for reading file content.
		-t_lexer	lexer 			 : for cathing while for and there args for exp the time they will have to take ...
		-int 		check_repeat 		 : for checking if thers any loop inside loop
		-double 	main_loop_time		 : for having the total time of the main_loop
		-int		total_of_loops		 : for knowing how much loops are in the main loop

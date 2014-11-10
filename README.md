progettoSVM
===========

match program with
	x::xs -> if x = "END" then end else Esegui (PC (split "" x)) :: (run_svm xs)
			
split (x : char) (lst : string list) : string list list
	-> [ ["MOV"];["[35]"];[23] ]

PC (lst : string list list) : type_pc = 
	match lst with
	[] -> 
	|x::y::z when x = "MOV" -> let mov1 = 
					type_pc {nome : x
						arg1 : y
						arg2 : z}
let Esegui (funz : type_pc) : 

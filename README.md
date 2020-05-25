# nfa-tester

A program to check if the given string is acceptable by the nfa which is converted from the regex form input.

Test run:

	/*
		Input:
			a.(b*+a)+b //regex input. 
			8	//number of strings to test.
			abbbbbbb
			ab
			b
			aa<
			aaa
			abab
			aabb
			bb
		Output:
			Accepted
			Accepted
			Accepted
			Accepted
			Rejected
			Rejected
			Rejected
			Rejected
	*/
 

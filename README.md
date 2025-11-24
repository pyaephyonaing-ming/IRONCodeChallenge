OldPhoneKeypad – C# Coding Challenge			
			
	Overview		
	This project simulates an old mobile phone keypad that converts a sequence of numeric key presses into alphabetic text - similar to how texting worked on classic phones.		
	Each key from 2–9 represents multiple letters, and pressing the same key multiple times cycles through those letters. 		
	The * key functions as backspace, and the # key indicates Send (end of input).		
			
	Given a string of keypad inputs consisting of digits 0–9, *, spaces, and ending with a #, convert the sequence into the correct textual message.		
	For example:		
	2 → A		
	22 → B		
	222 → C		
			
	If two characters use the same key, a pause (space ' ') is used between them.		
	Example:		
	222 2 22# → C A B → Output: CAB		
			
	Assumptions:		
	. Input always ends with #		
	. Characters allowed: 0–9, *, ' ', #		
	. The * key performs a backspace (deletes the previous character)		
	. Spaces are used to separate letters typed from the same button		
	Examples:		
	33# → E		
	227*# → B		
	4433555 555666# → HELLO		
	8 88777444666*664# → TURING		
	444777666 660777766633389277733*33# → IRON SOFTWARE		
			
	How It Works		
	Key	Letters	
	1	& ' (	
	2	A B C	
	3	D E F	
	4	G H I	
	5	J K L	
	6	M N O	
	7	P Q R S	
	8	T U V	
	9	W X Y Z	
	0	(Space)	
	*	Backspace	
	#	Send	

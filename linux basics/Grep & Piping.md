
grep is a command used to look up a word, phrase, or pattern inside a text file. 

Examples:

		grep "hello" test.txt 

		grep "hello" /etc/passwd

And since grep is case sensitive when used alone, we add -i to make it case insensitive.

Example:

		grep -i "hello" Desktop/test.txt

It also can be used without the quotations in some cases -> grep hello .....

Piping is actually directing the result of a specific search into the grep to look for a specific word.

Example: 
		cat text.txt | grep -i "hello"
	so in this case the result of the cat text.txt will be directed to the grep by the "|" (pipe) and then it will use grep to search for the "hello" word in this result and gives you the final output.

locate command is used to locate the file location by only its name. 

Example: 

		locate text.txt

we can use grep with it in order to narrow down the results.

Example: 

		locate text.txt | grep /usr

also we can search for all the results of a specific extension. 

Example: 

		locate "*.txt" | grep "text"

we can us -c to specify the number of results we have.

Example: 

		locate -c proxychains

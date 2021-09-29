###  The name of module : Scrambled_text
> This modules involves four functions that return randomly shuffled letters of one word.
###  Function names: 
```
> scrambled_first_last ("  ")
> scrambled_first ("   ")
> scrambled_all ("   ")
> scrambled_upper_lower ("   ")

```

###  Import
```
> In order to import the main module:
> Import scrambled_texts
```
```
> In order to import each function:
> scrambled_texts.scrambled_first_all ("   ")
> scrambled_texts.scrambled_first ("   ")
> scrambled_texts.scrambled_all ("   ")
> scrambled_texts.scrambled_upper_lower ("   ")

```
###  Usage
> All functions take a string as its first input argument and return scrambled letters of given text.
> 1) This function shuffles all the letters in a word except first and last letters.
```
> scrambled_first_last('Scrambling words is very interesting.')
> Simcnrblag wdors is vrey itnresnetig.
```                                                        
> 2) This function shuffles all the letters of a word except first letter.
```
> scrambled_first('Scrambling words is very interesting.')
> Sblnmcragi wdors is very itnsiretgen.
```
> 3) This function shuffles all the letters of a word.
```
> scrambled_all('Scrambling words is very interesting.')
> albnrcmiSg wsdro is very ntsritneige.
```
> 4) This function returns randomly some letters to lowercase and uppercase.
```
> scrambled_upper_lower('Scrambling words is very interesting.')
> ScrAmbLINg wORdS iS VERy iNtErESTINg.
```

###  Error Message
> These functions should be used with only string arguments. Numerical arguments raises error message.
```
> scrambled_all('Scrambling words is very intere34sting.')
> TypeError: The argument that you entered should not contain numerical statement ({34}). 
> Because the phenomenon of scrambled text works well only for letters. Please enter a text without numbers!
```
### Reference
> https://www.geeksforgeeks.org/python-scramble-words-from-a-text-file/


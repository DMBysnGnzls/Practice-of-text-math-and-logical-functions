# Practice-of-text-math-and-logical-functions
REPOSITORY 1

<b>What are TEXT functions?</b><br>
Excel is mostly about the numerical data, but at times you can come across the data which has too much text and that is the time when Text Functions in Excel will help you to simplify the things easily.<br>

<b>Usage Scenarios:</b><br>
-Conversion from lower case to upper case.<br>
-Used to find the substring withing a string.<br>
-Used to extract substring from a string.<br>
-List specific words or characters from a string.<br>

<b>LEN Function</b><br>
The Microsoft Excel LEN function returns the length of the specified string.<br>

<b>TRIM Function</b><br>
The Microsoft Excel TRIM function returns a text value with the leading and trailing spaces removed. You can also use the TRIM functions to remove unnecessary spaces between words in a string.<br>

<b>UPPER Function</b><br>
The Microsoft Excel UPPER function allows you to convert text to all uppercase.<br>

<b>LOWER Function</b><br>
The Microsoft Excel LOWER function allows you to convert to all lowercase.<br>

<b>SUBSTITUTE Function</b><br>
The Microsoft Excel SUBSTITUTE function replaces a set of characters with another.<br>
>Parameters<br>
text – The original string to use to perform the substitution.<br>
old_text – The existing characters to replace.<br>
new_text – The new characters to replace old_text with.<br>
nth_appearance – Optional. It is the nth appearance of old_text that you wish to replace. If this parameter is omitted, then every occurrence of old_text will be replaced with new_text.<br>

<b>REPLACE Function</b><br>
The Microsoft Excel REPLACE function replaces a sequence of characters in a string with another set of characters.<br>
>Parameters<br>
old_text – The original string value.<br>
start – The position in old_text to begin replacing characters.<br>
number_of_chars – The number of characters to replace in old_text.<br>
new_text – The replacement set of characters.<br>

<b>FIND Function</b><br>
The Microsoft Excel FIND function returns the locations of a substring in a string. The search is case sensitive.<br>
>Parameters<br>
substring – The substring that you want to find.<br>
string – The string to search within.<br>
start_position – Optional. It is the position in the string where the search will start. The first position is 1. If the start position is not provided, the FIND function will start the search at the beginning of the string.<br>

<b>LEFT Function</b><br>
The Microsoft Excel LEFT function allows you to extract a substring from a string, starting from the left most character.<br>
>Parameters<br>
text – The string that you wish to extract from.<br>
number_of_characters – Optional. It indicates the number of characters. If this parameter is omitted, only 1 character is returned.<br>

<b>RIGHT Function</b><br>
The Microsoft Excel RIGHT function allows you to extract a substring from a string, starting from the left most character.<br>
>Parameters<br>
text – The string that you wish to extract from.<br>
number_of_characters – Optional. It indicates the number of characters. If this parameter is omitted, only 1 character is returned.<br>

<b>MID Function</b><br>
The Microsoft Excel MID function extracts a substring from a string (starting at any position).<br>
>Parameters<br>
text – The string that you wish to extract from.<br>
start_position – The position in the string that you will begin extracting from. The first position in the string is 1.<br>
number_of_characters – The number of characters that you wish to extract. It is mandatory when the MID function is used as a Worksheet function, but optional in VBA. (if you omit this parameter in VBA, the MID function will return all characters after the start_postion).<br>

<b>CONCATENANTE Function</b><br>
The Microsoft Excel CONCATENATE function allows you to join 2 or more strings together.<br>

# TEXT-FUNCTION
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/17980f14-2f7f-44e3-a6bc-2bdc937996ca)

# NUMERIC-FUNCTION
<b>LIST OF NUMERIC FUNCTION</b><br>

<b>ABS</b><br>
-Returns the absolute value (i.e the modulus) of a supplied number<br>
-ABS function below returns the absolute value of a negative number<br>
-The absolute value of 0 is 0.<br>
-The absolute value of a positive number is the same positive number<br>


<b>SIGN</b><br>
-Returns the sign (+1, -1 or 0) of a supplied number<br>
-If number is greaten than zero,the SIGN function will return 1.<br>
-If number is equal to zero,the SIGN function will return 0.<br>
-If number is less than zero, the SIGN function will return 1.<br>

<b>GCD</b><br>
-Returns the Greatest Common Divisor of two or more supplied number<br>
-The Greatest Common Divisoi is the largest positive integer that divides the number without a remainder.<br>
                                                
<b>LCM</b><br>
-Returns the Least Common Multiple of two or more supplied numbers<br>
-The Least Common Multiple is the smallest integer that can be divided by all the numbers provided.<br>

<b>CEILING & FLOOR Functions</b><br>
-The Excel CEILING function rounds a given number up to the nearest specified multiple.<br>
-The Excel FLOOR function rounds a given number down to the nearest specified multiple.<br>

![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/666b95ef-a954-4166-8dd5-7b17cccf0262)


<b>EVEN Function</b><br>
-The Excel EVEN function returns the next even integer after rounding a given number up.<br>
-The EVEN function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative).<br>

![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/3d20b41a-0c21-4fe0-beb8-01d1ba295090)


<b>ODD Function</b><br>
-The Excel ODD function returns the next odd integer after rounding a given number up.<br>
-The ODD function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative).<br>

![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/746c52f7-0202-4ac1-9d51-6f8c060210db)


<b>ROUND Function</b><br>
-The Excel ROUND function returns a number rounded to a given number of digits.<br>
-The ROUND function can round to the right or left of the decimal point.<br>

![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/3432ca88-0dd4-4d62-91ac-189125997328)


<b>TRUNC Function</b><br>
-The Excel TRUNC function returns a truncated number based on an (optional) number of digits.<br>
-For example, TRUNC (4.9) will return 4, and TRUNC (-3.5) will return -3.<br>
-The TRUNC function does no rounding, it simply truncates as specified.<br>

![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/d97e8167-3239-450b-8aea-59ddd34203da)


# MATH-FUNCTION
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143982031/e3abd0d5-b2f1-401f-b4f7-1fa64ba5f135)
![image](https://github.com/nthnlgmz/Practice-of-text-math-and-logical-functions/assets/143614589/67aaf85d-fcc6-438e-8f74-4add805c6ef1)

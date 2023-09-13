# Practice-of-text-math-and-logical-functions
REPOSITORY-1

# TEXT-FUNCTIONS

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

>![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/666b95ef-a954-4166-8dd5-7b17cccf0262)


<b>EVEN Function</b><br>
-The Excel EVEN function returns the next even integer after rounding a given number up.<br>
-The EVEN function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative).<br>

>![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/3d20b41a-0c21-4fe0-beb8-01d1ba295090)


<b>ODD Function</b><br>
-The Excel ODD function returns the next odd integer after rounding a given number up.<br>
-The ODD function always rounds numbers up (away from zero) so positive numbers become larger and negative numbers become smaller (i.e. more negative).<br>

>![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/746c52f7-0202-4ac1-9d51-6f8c060210db)


<b>ROUND Function</b><br>
-The Excel ROUND function returns a number rounded to a given number of digits.<br>
-The ROUND function can round to the right or left of the decimal point.<br>

>![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/3432ca88-0dd4-4d62-91ac-189125997328)


<b>TRUNC Function</b><br>
-The Excel TRUNC function returns a truncated number based on an (optional) number of digits.<br>
-For example, TRUNC (4.9) will return 4, and TRUNC (-3.5) will return -3.<br>
-The TRUNC function does no rounding, it simply truncates as specified.<br>

>![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/d97e8167-3239-450b-8aea-59ddd34203da)


# MATH-FUNCTIONS
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143982031/e3abd0d5-b2f1-401f-b4f7-1fa64ba5f135)

<b>POWER Function</b><br>
>👉The POWER function is used to calculate a number raised to a specified power.  
>👉Syntax: =POWER(number, power)  
>👉Example: If you want to calculate 2 raised to the power of 8, you can use =POWER(2, 3), which will return 256.  
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/8182931e-2121-414f-ac9b-04f7b2e3ef24)

<b>SQRT Function</b><br>
>👉The SQRT function is used to find the square root of a number.<br>
>👉Syntax: =SQRT(number)<br>
>👉Example: To find the square root of 16, you can use =SQRT(16), which will return 4.<br>
>👉The SQRT function will return an error if you attempt to find the square root of a negative number because the square root of a negative number is not a real number.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/97540c9a-d7aa-418e-8e77-c1543e20db4f)

<b>QUOTIENT Function</b><br>
>👉The QUOTIENT function is used to find the integer portion of the result of dividing one number by another.<br>
>👉Syntax: =QUOTIENT(numerator, denominator)<br>
>👉Example: If you want to find the integer quotient of 12 divided by 2, you can use =QUOTIENT(12, 2), which will return 6. This function returns the whole number portion of the division result.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/8a6dd2cd-713d-40ca-afdb-77ee45b9aa91)

<b>MOD Function</b><br>
>👉The MOD function returns the remainder when one number (the dividend) is divided by another number (the divisor).<br>
>👉Syntax: =MOD(number, divisor)<br>
>👉Example: If you want to find the remainder when 10 is divided by 3, you can use =MOD(10, 3), which will return 1 because 10 divided by 3 is 3 with a remainder of 1.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/ac8124e9-e4d8-47b5-9541-2f60f0a3258b)

<b>MIN Function</b><br>
>👉The MIN function returns the minimum value from a range of numbers.<br>
>👉Syntax: =MIN(number1, [number2], ...)<br>
>👉Example: If you have a range of numbers in cells A1 to A5 and you want to find the minimum value in that range, you can use =MIN(A1:A5).<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/543dad20-6054-48b9-8c17-552091f85d12)

<b>MAX Function</b><br>
>👉The MAX function returns the maximum value from a range of numbers.<br>
>👉Syntax: =MAX(number1, [number2], ...)<br>
>👉Example: If you have a range of numbers in cells A1 to A5 and you want to find the maximum value in that range, you can use =MAX(A1:A5).<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/6f37e06d-9e0e-4996-abf7-d8d8c6f56d50)

<b>AVERAGE Function</b><br>
>👉The AVERAGE function calculates the arithmetic mean of a range of numbers.<br>
>👉Syntax: =AVERAGE(number1, [number2], ...)<br>
>👉Example: Suppose you have a dataset of students' quiz scores, and you want to calculate the average score for students who scored above 40 in Quiz 2. You can use the AVERAGEIFS function as follows:<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/1593d59b-de64-4411-aeb7-db0367b8c1f2)

<b>AVERAGEIFS Function</b><br>
>👉The AVERAGEIFS function calculates the average based on one or more criteria.<br>
>👉Syntax: =AVERAGEIFS(average_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)<br>
>👉Example: Suppose you have a dataset with product information, including their prices, colors, and the countries they are sold in. You want to calculate the average price for each product group (e.g., iPhone, Blackberry, Samsung, Realme, Huawei). To achieve this, you can use the AVERAGEIFS function in Excel.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/02c1dba1-0070-46b1-a17a-449e451b7ec4)

<b>COUNT Function</b><br>
>👉The COUNT function is used to count the number of cells in a range that contain numbers or numeric values.<br>
>👉Syntax: =COUNT(value1, [value2], ...)<br>
>👉Example: You have a list of values in column A, and you want to count how many of these cells contain numeric values.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/e119b418-09bf-493f-874e-dd0dc9447c66)

<b>COUNTA Function</b><br>
>👉The COUNTA function counts the number of cells in a range that are not empty (contain any value, including text, numbers, or errors).<br>
>👉Syntax: =COUNTA(value1, [value2], ...)<br>
>👉Example: Let's say you have a dataset in which you want to count the total number of non-empty cells. In your dataset, you have a column named "VALUE," and you want to count how many cells in this column contain any type of value, whether it's text, numbers, or even empty strings. You can use the COUNTA function for this purpose.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/bb31875d-547e-4fd3-97cc-65b184bca979)

<b>COUNTBLANK Function</b><br>
>👉The COUNTBLANK function counts the number of empty cells (cells that contain nothing, including empty strings) in a range.<br>
>👉Syntax: =COUNTBLANK(range)<br>
>👉Example: Let's say you have a dataset containing employee information, including their Employee ID, Salary, and Commission (Comm). You want to count how many employees have missing values (blanks) in the "Comm" column. To do this, you can use the COUNTBLANK function.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/10105766-8341-43a2-a4ad-318f516829aa)

<b>SUM Function</b><br>
>👉The SUM function is used to add up a range of numbers or values.<br>
>👉Syntax: =SUM(number1, [number2], ...)<br>
>👉Example: If you have a range of numbers in cells A1 to A5 and you want to find the total sum of these numbers, you can use =SUM(A1:A5). Excel will add all the numbers in the specified range.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/fde5505d-31c7-44ff-b491-3ae8491a8818)

<b>MEDIAN Function</b><br>
>👉The MEDIAN function calculates the middle value in a range of numbers. It's useful for finding the median of a dataset.<br>
>👉Syntax: =MEDIAN(number1, [number2], ...)<br>
>👉Example: You have a dataset with several numbers in the "NUM" column, and you want to calculate the median of these numbers. The MEDIAN function is used for this purpose.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/48d9a15b-e9a3-4676-8681-5250f8b1ead5)

<b>LARGE Function</b><br>
>👉The LARGE function is used to find the "n-th" largest value in a range.<br>
>👉Syntax: =LARGE(array, k)<br>
>👉You have a dataset with student names, their total marks, and their corresponding ranks. You want to find and display the scores of students based on their rank. To find the score for the student with rank 1, you can use the LARGE function.<br>
![image](https://github.com/DMBysnGnzls/Practice-of-text-math-and-logical-functions/assets/143614589/cbf44b70-7fe7-45cb-95f6-1808278a9cd0)
>

# LOGICAL-FUNCTIONs
<b>What are logical functions?</b><br>
-A LOGICAL FUNCTION is one that evaluates an expression and returns a Boolean result. <br>
>-For example, imagine a series of cells that represent employees last name. If you are interested to know which cell doesn't have a name, you can use a function. <br>
>-On the other hand, imagine you have a cell that is supposed to indicate when must you receive a discount, you can use a conditional function to check it. <br>

-Most, if not all, logical functions check a condition and render a result. <br>

<b>IF Function</b><br>
-The Microsoft Excel IF function returns one value if the condition is TRUE, or another value if the condition is FALSE <br>
>Syntax <br>
>=IF( condition, value_if_true, [value_if_false])
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/4154be65-e52a-4c23-879a-a44715030295)


<b>AND Function</b><br>
-The Microsoft Excel AND function returns TRUE if all arguments evaluate TRUE else return FALSE. <br>
>Syntax <br>
>=AND(condition1, [condition2], ...)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/fd26be52-ce70-4387-a3af-824f907415e0)


<b>OR Function</b><br>
-The OR function in Excel returns TRUE if any of the conditions are true and returns FALSE if all conditions are false. <br>
>Syntax <br>
>=OR( condition1, [condition2, ... condition_n])<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/78b0527a-6bbd-447d-b5a4-3c62dcdadc91)


<b>NOT Function</b><br>
-The Microsoft Excel NOT function is used to check if one value is not equal to another If we give TRUE, it will return FALSE and when given FALSE, it will return TRUE. <br>
>Syntax <br>
>=NOT(logical)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/c106a76e-3f08-4d84-b756-1da246e2e6bf)


<b>XOR Function</b><br>
-The XOR Function was introduced in Excel 2013 and is available under Excel Logical functions. It is a logical "exclusive OR" function.<br>
-For two given logical statements, the XOR function would return TRUE if one of the statements is true and FALSE if both statements are true. If neither of the statements is true, it also returns FALSE. <br>
>Syntax<br>
>=XOR(logical1, [logical2],...)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/4a85c07e-3459-45fe-904d-58ad825fda66)


<b>ISBLANK Function </b><br>
-The Microsoft Excel IF function returns one value if the condition is TRUE, or another value if the condition is FALSE. <br>
>Syntax<br>
>=IF( condition, value_if_true, [value_if_false])<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/c0b783c9-a340-459d-9512-c80322bc0c7e)


<b>IFERROR Function</b><br>
-The Microsoft Excel IFERROR function returns an alternate value if a formula results in an error.<br>
-It will check for errors such as #N/A, #VALUE!, #REF!, #DIV/O!, #NUM!, #NAME? or #NULL <br>
>Syntax <br>
>=IFERROR (value, value_if_error)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/7ba7a8bd-ba21-464d-a476-38693a5d6240)


<b>SUMIF Function</b><br>
-You use the SUMIF function to sum the values in a range that meet criteria that you specify. <br>
-For example, suppose that in a column that contains numbers, you want to sum only the values that are larger than 5. You can use the following formula: =SUMIF(B2:B25,">5")<br>
>Syntax<br>
>=SUMIF(range, criteria, [sum_range])<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/791f57cb-112a-4bdc-a302-7dfd7b34841d)


<b>COUNTIF Function</b><br>
-Use COUNTIF, one of the statistical functions, to count the number of cells that meet a criterion; for example, to count the number of times a particular city appears in a customer list.<br>
>Syntax<br>
>=COUNTIF(range, criteria)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/30306be6-9321-48ec-9a24-68f15f472975)


<b>IFNA Function</b><br>
-The IFNA function in Excel returns an alternate value as specified by the user if a formula results in an #N/A error. <br>
>Syntax <br>
>=IFNA(value, value_if_na)<br>
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/611cf88f-3101-4cf7-993e-28d7d7b84e83)
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/aac37841-59fa-4f90-b50d-5434d6bf88d7)
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/21731d9f-a032-4ec3-bf3b-c31424017030)
![image](https://github.com/ralphgrm/Practice-of-text-math-and-logical-functions/assets/134179620/eb3ec924-b0b4-4706-af18-c6e117607bb5)


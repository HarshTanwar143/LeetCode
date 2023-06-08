### Integer to Roman
## Medium

Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.
<br> 
Symbol       Value<br> 
I             1<br> 
V             5<br> 
X             10<br> 
L             50<br> 
C             100<br> 
D             500<br> 
M             1000<br> 
For example, 2 is written as II in Roman numeral, just two one's added together. 12 is written as XII, which is simply X + II. The number 27 is written as XXVII, which is XX + V + II.
<br> 
Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not IIII. Instead, the number four is written as IV. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as IX. There are six instances where subtraction is used:
<br> 
I can be placed before V (5) and X (10) to make 4 and 9. <br> 
X can be placed before L (50) and C (100) to make 40 and 90. <br> 
C can be placed before D (500) and M (1000) to make 400 and 900.<br> 
Given an integer, convert it to a roman numeral.<br> 
<br> 
 

Example 1:

Input: num = 3
Output: "III"
Explanation: 3 is represented as 3 ones.
Example 2:
<br> <br> 
Input: num = 58
Output: "LVIII"
Explanation: L = 50, V = 5, III = 3.
<br> <br> 
Example 3:

Input: num = 1994
Output: "MCMXCIV"
Explanation: M = 1000, CM = 900, XC = 90 and IV = 4.
 

Constraints:

1 <= num <= 3999

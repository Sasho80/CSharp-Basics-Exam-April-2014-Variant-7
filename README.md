
Problem 1 – Fruit Market
The local fruit market offers fruits and vegetables with the following standard price list:
•	banana  1.80
•	cucumber  2.75
•	tomato  3.20
•	orange  1.60
•	apple  0.86	The market owner decided to introduce the following discounts:
•	Friday  10% off for all products
•	Sunday  5% off for all products
•	Tuesday  20% off for fruits
•	Wednesday  10% off for vegetables
•	Thursday  30% off for bananas
Write a program that helps the fruit market owner to calculate the total price for orders that consist of day, 3 products with quantities.
Input
The input data should be read from the console. The input data consists of exactly 7 lines:
•	At the first line you will be given the day of week. 
•	At the next 6 lines you will be given: quantity1, product1, quantity2, product2, quantity3, product3.
The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
You have to print at the console the total price for the specified 3 products at the specified day of week.
Constraints
•	The day of week is one of the values: Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, and Sunday. 
•	The product quantities (quantity1, quantity2, quantity3) will be a number in the range [1…100], with up to 2 digits after the decimal point. The will be used "." as decimal separator.
•	The products names (product1, product2, product3) is one of the values: banana, cucumber, tomato, orange, and apple.
•	The fruits are banana, orange and apple. The vegetables are tomato and cucumber.
•	The total price should be rounded to exactly 2 digits after the decimal point (use "." as decimal separator).
•	Allowed work time for your program: 0.1 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output		Input	Output		Input	Output		Input	Output
Friday
3
banana
5
tomato
2      
       24.21

Tuesday
cucumber			
1.5
apple
2.50
orange
0.5     
       5.83

Monday
10
tomato
6
cucumber
10      
         64.50	
Thursday
3
banana
6.5
apple
2.33
tomato	
        16.83

Problem 3 – Wine Glass
Bulgarians are famous for being enchanted by the magic of the red wine. Its magic is very powerful and yet unpredictable. Some people report being struck by a memory loss charm, others lose control over their speech, to others it acts like a love potion. You’re asked to help the Bulgarians by printing a few of their beloved magical wine glasses for them.
Input
The input data should be read from the console.
•	You have an integer number N (always even number) specifying the height of the wine glass.
The input data will always be valid and in the format described. There is no need to check it explicitly.
Output
The output should be printed on the console. You should print the wine glass on the console following the examples below.
•	The glass has exactly N rows, each of which contains exactly N symbols. 
•	The first row should contain the backslash (“\”) symbol, a total of (N-2) asterisks (“*”) and the slash (“/”) symbol.
•	The second row should contain exactly one dot (”.”) before the backslash, one after the slash and two less (compared to the row above) asterisks between the slash and backslash.
•	The third row should contain one more dot at each side and two less asterisks and so on, until the (N /2) row, where there should be no asterisks between the slashes.
•	On the next (N/2)-2 rows, if N >= 12 or (N/2)-1 rows, if N < 12, you should print the stem that should look like the following: a count of (N/2)-1 dots (“.”), followed by two vertical lines (“|”) and (N/2)-1 dots after the lines. The remaining one or two rows (up to a total count of N) should be filled with exactly N dashes (“-”) on each row.
Constraints
•	The number N will be an even integer between 4 and 60, inclusive.
•	Allowed working time for your program: 0.1 seconds.
•	Allowed memory: 16 MB.
Examples
Input	Output				
6
\****/
.\**/.
..\/..
..||..
..||..
------	
Input	Output
8	
\******/
.\****/.
..\**/..
...\/...
...||...
...||...
...||...
--------

Input	Output
12	
\**********/
.\********/.
..\******/..
...\****/...
....\**/....
.....\/.....
.....||.....
.....||.....
.....||.....
.....||.....
------------
------------



# What are Regular Expressions?

A **Regular Expression** (short regex or regexp) is a sequence of characters that define a search pattern, which is usually used by string searching algorithms for "find" or "find and replace" operations on strings, as well as in input validation. 

## Why use regular expressions?
Below are some of the use cases where regular expressions fit the best:
• You have a huge text with phone numbers in **different formats**, you need to find and replace them with Xs for publication purposes. For example: "(100)-100-1000" -> "(100)-XXX-XXXX"

• You want to check if the user has given correct **email**, **phone number**, **IP address** or any form of data that has a specific form.

• You need to **rename** one of your variables, but some functions contain that variable name too. Regex is the solution to only select the variable names excluding the function names that include that word.

• You need to **reformat** a text and get rid of a special character with some conditions based on the location of that character.

All the scenarios above will fall into two categories, either **Search** or **Replace**.

There are many cases where regex can save you hundreds, if not thousands, of lines of code. 
In this series, we will learn how to write the rules, and see real use cases and scenarios implemented in different languages.

> **Regular expressions** originated from research in the 1950s in the field of mathematics. Years later, the principles and ideas derived from this research made their way into the **Unix** world, as well as the Perl language and utilities such as grep. 
For many years, regular expressions were the exclusive domain of the Unix community, but this has changed, and now regular expressions are supported in a variety of forms on every computing platform.

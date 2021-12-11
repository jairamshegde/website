---
title: "Post with TOC"
tags:
 - basics
 - website
toc: true
toc_label: "Table of Contents"
toc_icon: "cog"

---
Dave watched as the forest burned up on the hill, only a few miles from her house. 
The car had been hastily packed and Marta was inside trying to round up the last of the pets. 
Dave went through his mental list of the most important papers and documents that they couldn't leave behind. 
He scolded himself for not having prepared these better in advance and hoped that he had remembered everything that was needed. 
He continued to wait for Marta to appear with the pets, but she still was nowhere to be seen.

## Random English Paragraph

If you can imagine a furry humanoid seven feet tall, with the face of an intelligent gorilla and the braincase of a man, 
you'll have a rough idea of what they looked like -- except for their teeth.The canines would have fitted better in the face of a tiger, 
and showed at the corners of their wide,thin-lipped mouths, giving them an expression of ferocity.

## Lists
collection of items
### unordered list
* A
* B
* C
### Ordered List
1. One
2. Two
3. Three

## Code block

```python
# Program to display the Fibonacci sequence up to n-th term

nterms = int(input("How many terms? "))

# first two terms
n1, n2 = 0, 1
count = 0

# check if the number of terms is valid
if nterms <= 0:
   print("Please enter a positive integer")
# if there is only one term, return n1
elif nterms == 1:
   print("Fibonacci sequence upto",nterms,":")
   print(n1)
# generate fibonacci sequence
else:
   print("Fibonacci sequence:")
   while count < nterms:
       print(n1)
       nth = n1 + n2
       # update values
       n1 = n2
       n2 = nth
       count += 1
```

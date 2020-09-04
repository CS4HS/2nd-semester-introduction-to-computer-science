# Supplement Lesson 01: Binary Day (True North Edition)

## Learning Objectives

Students will be able to...

* Define and identify: **binary**
* Describe different representations of data
* Represent decimal numbers in binary

## Materials/Preparation

* [Do Now][]
* [Associated Reading](https://tealsk12.github.io/2nd-semester-introduction-to-computer-science/readings.md.html#associatedreadings/2.1)
* Index cards for binary activity (at least 1 per student)
* Scissors
* 8.5" x 11" printer paper, each page has a large number (2^n) written on it (1, 2, 4, 8, 16, 32, ...)
* Read through the do now and lesson so that you are familiar with the requirements and can assist students as needed

## Additional Resources

* [CS Unplugged Binary Numbers][]

### Emphasize with students ...

#### BC ADST Mathmematics Computer Science 11 Content - Data Representation and Data Types

The computer only can store a value of 1 or 0 using high voltage or low voltage on the wire of 
logic gate output.  By connecting basic logic gates in a feedback configuration, logic components 
can remember it's previous charge or value;  hence, the hardware has "memory".  This forms the 
foundation of the integrated circuit, in all of our digital devices today.

Question for students to ponder on:  
If a computer uses 64 bits to represent integer numbers, what is the largest integer value possible?
If one of those 64 bits is used for representation "sign" (positive or negative), then what the 
range of possible numbers that can be represented?
But, what about very very big numbers, or very very small numbers?
Hint:  Another kind of system is used to represent floating point numbers https://www.geeksforgeeks.org/ieee-standard-754-floating-point-numbers/
---


## Pacing Guide

| **Duration**   | **Description** |
| ---------- | ----------- |
| 5 Minutes  | Do Now      |
| 45 Minutes | Lesson/Activity      |
| 5 Minutes | Debrief     |

## Instructor's Notes

### 1. Do Now

* Project [Do Now] questions on the screen
* Have students discuss how they used their fingers to count to 10, compared to how they counted to 1023.

### 2. Lesson/Activity

1. Explain **binary** compared to decimal: it is a different base of counting, specifically base-2.
2. Have students write | 1 | 2 | 4 | 8 | 16 | 32 | ... on the bottom of an index card spaced out about half an inch apart. Cut along the lines so that the numbers are each on a flap.
3. Announce any number and have students fold up the index card sections such that the numbers showing add up to the desired number.
4. Write on the board what the decimal number announced now looks like in binary (e.g. 9 = 1001).
5. Repeat with additional numbers until all students demonstrate understanding.
6. Choose students to walk up to the front of the classroom. Have them hold the place they represent and have a number (2^n) on a sheet of paper (so student's have a 1 or 2 or 4 or ... written on their paper).
Call out numbers and then have the students work together to decide if their number should be held up (representing a "1") or not.
7. What else can be represented by binary? Answer (ANYTHING!)
8. Show students this photo:

![Stary Night](starynight.png)
9. Explain how this is a digital representation of the artwork, but it's not immediately clear to see how this is represented with 0's and 1's.
10. Now you can have students look at a black & white example for more clarity:

![city scape](basic_city.png)

#### Pixel Level

![Pixel Level](Pixel_Level.png)
11. Explain to students that we can imagine saying 1 is black and 0 is white.
12. All data gets converted into binary values! Even music, video, and complex images!
13. Discuss how everything the computer reads gets turned into binary in the end, including the code that they will write in this class.
14. How could letters (a,b,c,...) be turned into binary?
15. How can letters be turned into numbers? a = 1, b = 2, c = 3.

### 3. Debrief

* Have students write down two things they learned in this lesson in their notebooks.

## Accommodation/Differentiation

## Forum discussion

[Lesson 2.01: Binary Day (TEALS Forums Account Required)](https://forums.tealsk12.org/c/2nd-semester-unit-2/2-01-binary-day)

[Do Now]:do_now.md
[CS Unplugged Binary Numbers]:http://csunplugged.org/binary-numbers/

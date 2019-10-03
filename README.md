# Programming for Math
**Goals (high level intended outcomes; for software, a Product Backlog)**  

 - To get an introduction into computational mathematics   
 - To develop a use of python outside general programming.
   
 -  To get a higher understanding of higher level mathematics   
   - Complete the four sections of the sage tutorial and its exercises.

**Boundaries / Scope (where the functions and responsibilities of the solution start and end / what it should do and what is left to other systems to do)**  
- Read through SDSU sage tutorial  
- Download a copy of Sage  
- Read through other Sage documentation  

**Success criteria (set of conditions to be satisfied at completion; must be measurable and verifiable, like a test)**  
- My own application that will successfully complete mathematical operations.  
- Weekly work log with screenshots and summaries to demonstrate activity.  

**Constraints (externally imposed limitations on system requirements, design, or implementation or on the process** used to develop or modify a system)  
- I am only a precalculus student; therefore, my mathematical knowledge does not extend that much past Calculus.

**Assumptions (things that are accepted as true or as certain to happen, without proof)**  
- The tutorial will be available for the duration of the semester.  
- I have all required software.  
- I have access to the internet throughout the semester.  


**Stakeholders (individuals or organizations having a right, share, claim, or interest in a system or in its possession of characteristics that meet their needs and expectations)**  
- Myself - for my own understanding and growth  
- Professor- for grade  
- Graduate Schools - Project will be added to portfolio and could help in getting into Graduate school or Research.  
- Perspective Employers - artifact will be added to my student portfolio which could help with getting a job.  

**Timelines (for software, a breakdown of high level goals like from the Product Backlog into time-bound smaller, more detailed tasks, like in Sprint Backlogs)** </br>
Week: </br>

1. Part 1. About this tutorial (2 hours)
2. Part 2. Sage as a Calculator - Arithmetic and Functions & Solving Equations and Inequalities (3 Hours)
3. Part 2 Sage as a Calculator - Calculus (3 Hours)
4. Part 2 Sage as a Calculator - Statistics and Plotting (3+ hours)
5. Part 3 Programming in Sage - Sage Objects (3 Hours)
6. Part 3 Programming in Sage - Programming Tools (3 Hours)
7. Part 3 Programming in Sage - Packages within  sage & Interactive Demonstrations (2 Hours)
8. Part 4 Mathematical Structures - Integers and Modular Arithmetic (3 Hours)
9. Part 4 Mathematical Structures - Groups (3 Hours)
10. Part 4 Mathematical Structures - Linear Algebra ( 3 Hours)
11. Part 4 Mathematical Structures - Rings (4 Hours)
12. Part 4 Mathematical Structures - Fields and Coding Theory (4 Hours)

**Week 1: About This Tutorial (Less than 1 Hour)** </br>
I downloaded the open-source sage software on to my computer, and saw the three methods to use sage: a command line, a shell that call on scripts, and an online notebook. I learned about tab completion which is a feature of sage that allows one to enter the first couple letters of a function and [TAB], which returns all functions that are similar to that function. Sage also has a feature to use x.[TAB], where x can be an integer and sage returns all functions that can work with x.

**Week 2:  Sage as a Calculator - Arithmetic and Functions & Solving Equations and Inequalities (3-4 hours)** </br>
Arithmetic and Functions introduces the basic aritmetic operators, and how sage processes commands through order of operations (PEMDAS). In Basic Aritmeric, I saw basic functions in algebra and trigonometry including sin(x), cos(x), abs(x) (absolute value), log(x)/ ln(x), exp(x) (which takes e to any power), and the major constants of pi and e. I also learned of some of the errors that can occur with sage; for example, when dealing with irrational numbers or an infinite amount of digits, computers can round off and perform inaccurate calculations. Additionally, computers process information in binary where humans have the decimal system and this can create a discrepancy in mathematics.

**Week 3: Sage as a Calculator - Calculus (2 hours)** </br>
This module covered the three basic problems in Integral and Differeintal Calculus, allowing me to learn limits, derivatives, integrals. When using sage for Calculus, it is important to define functions and then perform calculations. Starting with Limits, sage tries to find the function value at a certain x-value and sage can help with computing this; however, sage has a small problem when finding limits at discontinuities and this forces the user to use directional limits. It can also solve derivatives and derivatives at certain points with sage which leads to finding the tangent line to a function curve at a certain point, in other words the slope of any curve can be found at any point. Finally, sage can be used to find the integral (the opposite of the derivative) of a specific function, and definite integrals which can help find the area under a curve.

**Week 4: Sage as a Calculator - Statistics and Plotting (3 hours)** </br>
The statistics module shows the capabilites of what sage can do with a group of data points using basic functions such as average, mode, median, and standard variation. I can also combine certain functions to create new functions; for this module, I created the range() function by subtracting the value of the min() function from the value of the max() function. In the plotting module, I learned about how to graph defined functions on specified intervals. The graphs can be easily customized with choices of intervals, linestyles, colors, thickness, and more. Sage can also create graphs on 3D scales using a Java outlet.

**Week 5: Programming in Sage - Sage Objects (4+ Hours)** </br>
In the Sage Objects module, I learned mostly about the basic concepts and semantics of python which can help with programming in sage outside of functions that have already been made. Sage objects covers variables, booleans, strings, lists, sets, and more. I started out with finding the universe of an object, or what numerical field it belongs to, which can me understand what sage can do with that object. For example, the integer ,2, belongs to the integer field, and ,1/2, belongs to the rational field. With Booleans, I came across conditional statements and logical operators which can help with seeing if statments are true or false. Lists introduces arrays and how we can cut up lists with "slices", if we had a list, L = [1,2,3], then L[0:1] will return index 0 through 1. Sets are similar to lists, but they are not indexed and one can do special operations such as union and intersection with them. 

**Week 6: Programming in Sage - Programming Tools (3 hours)** </br>
This module further explored more of the programming side of sage than the math side. I learned if statments and how I can use conditionals to create code that decides what will be executed. I learned about for loops that can execute something for a fixed amount of times, along with while loops that iterate until a condition is no longer met. Additionally, the module showed functions that the user defines with or without parameters and then calls. Something new to me, was list comprehensions which were a quick way to create a list of data points such as [ k for k in [1 .. 20] if k % 2 == 0]. 

**Week 7: Programming in Sage - Packages within sage & Interactive Demonstrations (2 Hours)** </br>
This module goes over other packages or modules that sage developers create for users to utilize, sage showed off one package that specializes in modifying lists to create Groups. It also showed how to use these packages in the online notebook and some interactive applets that are accesible on the notebook. For example,  I was able to create an input box for text, a slider to pick a number, and a slider that helped in creating a graph. 

**Week 8: Mathematical Structures - Integers and Modular Arithmetic (4+ Hours)** </br>
This module begins with the concept of the ring of integers modulo which are all integers % some number. I learned how to create a field similar to the universes in week 5, that consisted of all numbers that were a remainder when divided by some number. I then learned how to perform arithmetic with these fields which creates a new field. The fields are useful because I can verify certain mathematical properties like the additive inverse, multiplicative inverse, and etc. Using the methods from list comprehensions, I can also find solutions such as a * x == b where you find elements in the field that meet these restrictions. The module also included the euclidean algorithm which is a more complex way of finding the gcd between two numbers. Integers and Modular arithmetic contain advanced topics in math that is very new and logic-heavy, so it seems that I am going to have to review this section a little longer.

**Week 9: Mathematical Structures - Groups (3 Hours)** </br>
This module provides an introduction to groups which is just a representation of a group of elelments, but a group is different from a set, list, or array. Sage allows the user to create groups of n amount of elements, and each element is represented in cycles or tuples. I learned how to take the products of elements and exponentiate elements. 

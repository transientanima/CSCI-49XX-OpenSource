# Lab 1  Tuesday January 15th, 2019 (in class lab)

## Github, Linux Command Line Instructions, Regular Expressions and Visual Programming

### Maintain a repository on github for all your lab work. Inside, you should create a markdown page for this lab's work. You will be graded at the end of the lab or at the latest by beginning of the next lab. To submit this assignment, create a text file with 2 lines. The first line should be a link to your github repository and the second link should be the link to your Lab 1 entry. Submit this as the only file to Submitty [https://submitty.cs.rpi.edu/index.php?semester=s19&course=csci4966](https://submitty.cs.rpi.edu/index.php?semester=s19&course=csci4966). 

> Markdown syntax is [here](https://help.github.com/articles/basic-writing-and-formatting-syntax/) and [here](https://guides.github.com/features/mastering-markdown/) 

a. Create and setup a Github account (You can skip this part if you already have one)

  1. Go through this tutorial to get familiar with [git and github](http://readwrite.com/2013/09/30/understanding-github-a-journey-for-beginners-part-1) and to set up a git hub account.

c. Create a repository under your Github account for all your lab work.

b. Create a bio page in your repository titled `bio.md`
  
  1. Please have your name and a photo in the markdown page . [Here is a sample page](https://github.com/mskmoorthy/Doc-ex1/blob/master/lab-1-sample.Md) 
  2. You can copy and paste screen shots as well as add text. Please add your github id and your slack handle

c. Reading assignments - make sure to reflect on these in a lab1.md file in your repository 
  
  1. Please read the 10 criteria of [Open Source Definition](http://opensource.org/osd) and understand why they are important.
  2. Please read Eric Raymond's article [Smart Questions](http://www.catb.org/esr/faqs/smart-questions.html) How to ask the question The Smart Way . 
    - Do you have more suggestions for How To Answer Questions in a Helpful Way (from your past experience)
    - List at least two.
  3. Please read chapter 3 of [Free Culture](http://www.free-culture.cc/freeculture.pdf)
   - Write a short paragraph ( 8 to 10 sentences) of what you got out of reading that chapter.
  
d. Linux 

  1. Boot linux (Ubuntu) through a USB, dual boot, or through Windows WSL (See [https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10) for WSL
    - Get familiar with the directory structure.
    - Practice with ls, cd, mkdir, chmod commands - when in doubt search the web to find the answer.
  2. Practice with grep, egrep commands
    - Look at the manual (`man grep`) to see how to use these commands. 
    - Read the first chapter in [Beautiful Code](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxpb3ZhbmFsZXh8Z3g6MjVjYWFmNjAwYTA0MmMxZA) about the development and implementation (in C) of a very simple grep  
  3. Install tree and get the directory structure. 
    - `sudo apt-get install tree`, or use the Ubuntu software install
    - `man tree`
    - Take a screenshot and add to `lab1.md`

e. Regex

  1. In your Foundations of Computer Science class you learned about Regular expressions. (If you have not taken Foundations of Computer Science class, please talk to the instructor for an explanation)  
  2. Please do the practice problems given [here](http://regexone.com/) (moving over Interactive Tutorial in the top right corner will get to this). 
    - To get full credit, do at least 7 problems.
    - Take a screenshot and add to `lab1.md`
  3. Go through the tutorials [here](https://regexcrossword.com/challenges/tutorial/puzzles/1) 
    - Do all the problems and at least four problems on beginner level [here](https://regexcrossword.com/challenges/beginner/puzzles/1 ).
    - Take a screenshot and add to `lab1.md`
  4. (Optional But Recommended) Do problem 11 in [adventofcode 2015](http://adventofcode.com/2015/day/11) (You may use regular expression) 


f. Play with [Snap](http://snap.berkeley.edu/) or [CSDT](https://community.csdt.rpi.edu/) or
[Blockly](https://blockly-games.appspot.com/) 
  
  1. Create some thing using either of the first two or solve [this](https://blockly-games.appspot.com/maze?lang=en&level=10&skin=0) using blockly
  2. Add to `lab1.md`


g. Reflection

 1. Pick an Open Source Project that might be interesting to evaluate
 2. Start thinking/finding a problem/project that interests you 
 3. Write a paragraph how you are doing this activity.
 4. Add to `lab1.md`
 5. Check out http://aosabook.org/en/index.html for a list of a number of open source projects and for a discussion of the architectures they use.s

<!--#### Revisit e. Replace with TOS activity on evaluating open source ... 
[foss2serve](http://foss2serve.org/index.php/Intro_to_FOSS_Project_Anatomy_(Activity)), [Evaluation](http://users.dickinson.edu/~braught/courses/cs491f17/projexpl.html)
[projects](http://foss2serve.org/index.php/HFOSS_Projects), [RCOS](https://rcos.io/projects), others.
-->
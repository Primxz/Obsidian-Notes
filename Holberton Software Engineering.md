[What are you doing this for?

- fundamentals over basic tools learning
- social cognitive conflict (learn by doing)
- AI is SUPPOSED to enhance work not replace doing it.
- don't be a fuckwit

#### **Computational Thinking** 

Four pillars of computational thinking: 

**Decomposition** 

Decomposition is the act of breaking down complex problems into more bite sized and manageable parts. 

**Pattern Recognition** 

When you find similarities between two different problems that allow for an easier way to solve or understand those problems easily. 

**Abstraction** 

Abstraction is when you filter out or disregard aspects or characteristics of a problem that are irrelevant or do not help you to figure out a problem. 

**Algorithmic Thinking** 

An algorithm is a set of steps that help solve problems. **Evaluation** Evaluation is when we critically analyse a solution to a problem that comprehensively asks if the solution to the problem is apt or not, and if not how it can be improved.

- Is it easily understood? (Is it fully decomposed)
- Is it complete? (Does it solve every aspect of the problem)
- Is it efficient? (Does it solve the problem or does it make the best use of the available resources)
- Does it meet it's design criteria

Design and analysis of algorithms 

What is an algorithm? 

A sequence of steps to solve a problem. We design algorithms to solve problems. One computer problem might have several solutions. The best solution is not always going to be the smaller algorithm (this is a misconception in coding) it's dependent on how efficient the complexity of the algorithm is. Design strategies

- Greedy Approach
- Divide & Conquer Approach
- Dynamic Programming Approach
- Randomization Approach
- Approximation Approach
- Recursive Approach
- Branch and Bound Approach

To analyse the feasibility of an algorithm you have to calculate the complexity of it. Asymptotic notations

- **Worst-Case Scenario** − Big Oh and Little Oh Notations
- **Best-Case Scenario** − Big Omega and Little Omega Notations
- **Average-Case Scenario** − Theta Notation

(having the best worst-case is said to be optimal) 


#### **What is an algorithm?


"An algorithm is a set of finite, well-defined steps or instructions designed to solve a problem or perform a computation."

Different types of algorithms:

Searching Algorithms
Recursive Algorithms
Sorting Algorithms
String Algorithms
Divide and Conquer Algorithms
Greedy Algorithms
Pathfinding Algorithms
Dynamic Programming Algorithms
Backtracking Algorithms
Graph Algorithms
Tree Algorithms
Mathematical Algorithms
Bit Manipulation

**What can algorithms do:?

Algorithms can be used in a variety of different applications:

Searching: Algorithms that review vast catalogues of data to find the file or archive you might be looking for.

Sorting: Algorithms that arrange data in an efficient and organised way.

Networking: Graph algorithms are used for routing, connectivity and finding shortest paths.

Databases: Algorithms help in indexing, searching, sorting and processing large amounts of data.

Artificial Intelligence: Algorithms are used for optimisation, decision-making and processing data.

**Advantages of Algorithms**

Efficiency
Accuracy
Reusability
Maintainability

**Characteristic of a good algorithm:**

Finiteness: The algo must stop after some time.
Definiteness: Every step must be clear.
Input: An algor may have zero or more inputs
Output: It must produce an output of some kind
Effectiveness: Each step should be simple enough to carry out in a reasonable time.

Examples of an algorithm can be as simple as a day to day routine.

1. Wake up
2. Take Shit
3. Get out of bed

(it's more like doing an action)

How to make a cheese toastie

1. Turn jaffe on
2. Spread butter on bread
3. apply cheese and ham
4. place in jaffe
5. close jaffe
6. wait 5 mins
7. open jaffe and serve.

#### **What is Pseudocode**

It's described as a high-level representation of algorithms that avoids programming language syntax while maintaining logic and structure.

Computers cannot execute this code, it's not readable by them nor is it really supposed to. It's supposed to help you plan out code.

**Examples of Pseudocode**



**4 Rules to writing pseudocode**

1. Captialise the initial word
2. Conclude multi-sections with end keywords
3. Write code that is clear concise and unmistakable
4. Test it (write it for real)



Actually Writing Pseudocode

ByRef = By Reference
ByVal = Creating a copy
(=) = assignment
(=/=) = Eqaulity
(!=) = inequality
(0 - a) = subtraction from zero
WHILE = enables loops
PROCEDURE = keyword for various actions in an algo
SEQUENCE = Instructions executed in order
WHILE = Represents a loop that continues while a condition in true
IF-THEN-ELSE = A conditional statement that directs the flow of the algorithm base on specific conditions.
REPEAT-UNTIL = A loop that continues until a condition is met, differing from WHILE by checking the condition at the end.
FOR = Another looping construct, typically used for count-controlled iterations.
CASE = Used for multiple conditional branches.
SUM = an accumulator
PRINT = To show a value

Attempt 1

set n to 1
while coutn < 3
print value
set while to n + 3
Endwhile

Attempt 2


While N <= 3 
Print Value
Set print to n + 3
Endwhile

Attempt 3

Set N to 1
While N <= 3
Print Value
Set While to N + 3

(ByVal ensures that that the functions parameter changes do not affect the original code but when original code is required ByRef is the appropriate option.)

Build an algorithm that:

1. Starts a counter to 1.
2. Starts an accumulator to 0.
3. Repeats a process until the counter reaches 5.
4. During each repetition:

- Adds the current counter value to a running total.
- Increases the counter by 1.

1. After the loop ends, displays the final total.

The intended result is the sum of the numbers from **1 to 5**, printed **once**, after the loop finishes.

1 SET N TO 1
2 SET SUM TO N
3 WHILE N <= 5
4 SET SUM TO SUM + N
5 SET N TO N + 1
6 ENDWHILE
7 PRINT SUM

WHILE N <= 5


SET SUM TO SUM + N
SET N TO 0

SET SUM TO SUM + 1
PRINT N 
ENDWHILE PRINT SUM


**How to Manually Trace (Run) Your Pseudocode**

To check your work before submitting it, you can perform a **hand-trace** of the algorithm using a simple table. This is a common technique in programming: you simulate the code step-by-step and track how the variables change.

Here is how to do it (you must fill the table yourself):

1. Create a table with columns:

- **Iteration**
- **N**
- **RESULT**

1. Start by writing the **initial values** before the loop starts:

- `N = 1`
- `RESULT = 1`

1. For each loop iteration:

- Write the current value of `N`
- Compute the new value of `RESULT` after multiplying
- Then compute the new value of `N` after the increment
- Move to the next row

When the loop finishes, the last value of **RESULT** is the final factorial value that will be printed.

This hand-tracing method is something you will use often when programming in C and other languages.

If the pseudocode is executed correctly, the final printed output will be:


What are our options


SET RESULT TO INPUT - INPUT + 1
WHILE  N <= INPUT
SET RESULT TO RESULT * N
SET N TO N + 1
SET RESULT TO 0
SET RESULT TO RESULT + N
SET N TO 0
WHILE RESULT <= INPUT
PRINT N 
ENDWHILE PRINT RESULT



1 SET N TO 1
2 SET RESULT TO INPUT - INPUT +1
3 WHILE N <= INPUT
4 SET RESULT TO RESULT * N
5 SET N TO N
6 ENDWHILE
7 PRINT RESULT


#### **Understanding Computer Operations**




`PC` (Program Counter) Holds the address of the next instruction to execute.

`CIR` (Current Instruction Register) Holds the instruction currently being executed.

`ACC` (Accumulator) Holds the numeric value used during calculations.

Initial state:

`PC = 0` `ACC = 0`


**Instruction Set**

The CPU understands the following instructions.

- `LOAD X`
    
    - Effect: `ACC` becomes `X`
    - After execution: `PC` **increases** by 1
- `ADD X`
    
    - Effect: `ACC` becomes `ACC + X`
    - After execution: PC **increases** by 1
- `PRINT`
    
    - Effect: `ACC` does not change
    - After execution: `PC` **increases** by 1
    - The value currently in `ACC` is considered the output of the program.
    - ### Program to Simulate

The program stored in memory is:

- `Address 0`: `LOAD 4`
- `Address 1`: `ADD 3`
- `Address 2`: `ADD 2`
- `Address 3`: `PRINT`

You must simulate execution starting from the initial state and continue until after the `PRINT` instruction is executed.

204 ÷ 16 = 12.75 = 12 R 21

12 ÷ 16 = 0.75 = 0 R 



12.75 


hate this shiiiiiiiiiiiiiiiiiiiiiiiiiiiit

#### **The Git and GitHub**

How to set up a repository:

1. git --version (just to be sure not really needed every time)
2. git config --global user.name studentaccount4fun
3. git config --global user.email 15707@holbertonstudents.com
4. initialise git (git init) 
5. create a project folder (directory) under /root
6. git status
7. actually make the repository on github
8. then connect = git remote add origin (your url for the repo)
9. To check if it's working type (git remote -v)


studentaccount4fun
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

git pull origin main --allow-unrelated-histories

git config --global credential.helper store


How to commit and push files:

Git commands:

In terminal:

ls = list directiory
cd = Change directory
mkdir = create new directory
touch = new note or file


In repository:


Origin  = 

Main = Your branch


git clone = setup repository in terminal
git fetch = fetches updates
git status = status of repository
git add = tracking new file
git diff = shows exact lines added and removed
git diff --staged = shows what you've staged that will go into next commit
git diff --cached = see what you've staged so far
git commit -m = commiting a file (this needs a description)
git add = adds file to staging area
git remote = lists shortnames of each remote handle you've specified
-v = lists remote handles as URLS
git branch -M main = sets your branch to main
git checkout -b "something" = creating and switching to a new branch
cat = opens file in a directory

git config --global credential.helper store

figure out later:

--oneline
--decorate
--graph
--all

git tag -a v1 -m "stable version"

If you're struggling with how you make changes to a document or how the process works brush up on this [link](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository).

What was I doing?

I just have extra commits.



https://github.com/studentaccount4fun/holbertonschool-github-flow.git

https://github.com/hbtn-edu/github-collab-basegit 
#### **Shell, Basics**

What is the shell?

"Simply put, the shell is a program that takes commands from the keyboard and gives them to the operating system to perform."

Shell Commands:

pwd = Print working directory
ls = list files and directories
cd = change directory
less = allows viewing a text file


moar shell comands

head = prints the first line of text files
tail = prints the end/last 10 lines of a text file
find = used to search for files in directories depending on how you type it out
wc = prints word count of a text file
sort = rearranges lines of a text file in the order specified
uniq = used to remove duplicate lines in text files
grep = used to search for specific lines in text files
tr = translates files into other things depending on what is specified
echo = prints text or can be used to edit text files

chmod u+x = Makes files in the shell executable







**Permissions**

[chmod](https://linuxcommand.org/lc3_man_pages/chmod1.html) - modify file access rights
[su](https://linuxcommand.org/lc3_man_pages/su1.html) - temporarily become the superuser
[sudo](https://linuxcommand.org/lc3_man_pages/sudo8.html) - temporarily become the superuser
[chown](https://linuxcommand.org/lc3_man_pages/chown1.html) - change file ownership
[chgrp](https://linuxcommand.org/lc3_man_pages/chgrp1.html) - change a file's group ownership

![[Pasted image 20261027144204.png]]

#!/bin/bash - start of every file
chmod u+x - to make scripts exe

Task 1 - Pretty simple, it asks for a script to switch users. The command su does that so the script is just (su betty).

Task 2 - a little more difficult but I looked up what commands print names in shell and came up with this. (whoami)

Task 3 - It's a little difficult when these commands can be interchanged for different things, but one you start getting creative it makes sense. It's chown betty hello. This I felt I had to intuit but it's possible.

Task 4 - This one is pretty self evident. I've been using touch to make files since the admissions portal lol.

5 - This one is actually so cheeky. It's the command for execute permissions and then the name of whoever. I honestly couldn't figure this one out so I searched it up.

6 - 

FIX THIS SHIIIIIIIIIIIIIIIIIIIIIIIIIIIIIT!!!!!!!!!


task 0 = echo "Hello, World"
task 1 = echo "\"(Ôo)'" (not sure why this one didn't work I don't think it has anything to do with the code itself as something else before it isn't correcting but if that means going into the terminal and doing something I'm fucked lol)
task 2 = cat /etc/passwd
task 3 = cat /etc/passwd /etc/hosts
task 4 = tail /etc/passwd
task 5 = head -n 10  5-firstlines (-n denotes the number of lines you want to print for a file)
task 6 = head -n 3 iacta 
task 7 = echo "Best School" > \\\*\\\\\'\"Best\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*:\)
task 8 = ls -la > ls_cwd_content
task 9 = tail -n 1 iacta >> iacta
task 10 =
task 11 =
task 12 =
task 13 =
task 14 =
task 15 =
task 16 =
task 17 =
task 18=
task 19 =
task 20 =
task 21 =
task 22 =



https://linuxcommand.org/lc3_lts0070.php







https://mywiki.wooledge.org/BashGuide/SpecialCharacters









### **Emacs**

Emacs aims to be a modular and granularly editable text editing software that allows users to customise it to their own liking.


Buffer: Where you read and write text.

#### **Dockers**
















### **Resources for all topicsssss** **

**Understanding Computational Thinking**
[Computational Thinking](https://www.bbc.co.uk/bitesize/topics/z7tp34j)
[What is computational thinking](https://www.youtube.com/watch?v=qbnTZCj0ugI)

**Flowcharts and Algorithms**
[Flowchart Symbols and Meaning](https://www.geeksforgeeks.org/dsa/an-introduction-to-flowcharts/)

[Tutorialspoint: Algorithm Baiscs](https://www.tutorialspoint.com/design_and_analysis_of_algorithms/index.htm)

**General Problem-Solving** 
[Khan Academy: Intro to Algorithms](https://www.khanacademy.org/computing/computer-science/algorithms)


[Crash Course Computer Science](https://www.youtube.com/watch?v=O5nskjZ_GoI](https://intranet.hbtn.io/rltoken/MuSv9jzwFo2G88KCwwzf2g)
[CPU Architecture Explained]([https://www.youtube.com/watch?v=GtVDTp826DE](https://intranet.hbtn.io/rltoken/h5_Q9CkcQfy5asQfTke63w)
[Crash Course Computer Science](https://www.youtube.com/watch?v=zltgXvg6r3k](https://intranet.hbtn.io/rltoken/_1-hl4bbRXinWkj9A-sxrw)
[Binary Numbers](https://www.tutorialspoint.com/article/binary-number-system)
[Hexadecimal Numbers](https://www.tutorialspoint.com/hexadecimal-number-system](https://intranet.hbtn.io/rltoken/dfPHctcRA0_IDt5iZ4rs9w)
[The Complete ASCII Table](https://www.asciitable.com](https://intranet.hbtn.io/rltoken/UGW9ymtONov2v5Y_WY21aQ)
["What is ASCII?”](https://www.computerhope.com/jargon/a/ascii.htm](https://intranet.hbtn.io/rltoken/quHMrsTbd7GIzksYAc5B0w)
[“Bitmap Graphics Explained”](https://www.computerhope.com/jargon/b/bitmap.htm](https://intranet.hbtn.io/rltoken/J1ii5lAFV1y87MYpFV8IaQ)
[All about Bitmap Images](https://www.youtube.com/watch?v=2mWc3YqlM7c](https://intranet.hbtn.io/rltoken/6qMprKbD9VhpmJ2xziirPw)
[Crash Course Computer Science](https://www.youtube.com/watch?v=26QPDBe-NB8](https://intranet.hbtn.io/rltoken/VUnF6euYuzqSTjCYoxWzCQ)
[What is an operating system?](https://www.ibm.com/think/topics/operating-systems](https://intranet.hbtn.io/rltoken/FHdu3q2jUjHFEltK9xRixA)
[OS Responsibilities Overview](https://www.geeksforgeeks.org/functions-of-operating-system/](https://intranet.hbtn.io/rltoken/x_q0qbXzwTsq_wXHpES0lA)
[Linux Filesystem Structure Explained](https://linuxhandbook.com/linux-directory-structure/](https://intranet.hbtn.io/rltoken/R42nLIBT1zn6s8BvaCA_3A)
[Absolute vs Relative Paths](https://www.geeksforgeeks.org/linux-unix/absolute-relative-pathnames-unix/](https://intranet.hbtn.io/rltoken/7nZQ-wgW_f4K8JDbrRgKsg)
[First-Come, First-Served (FCFS) Explained](https://www.geeksforgeeks.org/dsa/first-come-first-serve-cpu-scheduling-non-preemptive/](https://intranet.hbtn.io/rltoken/-frm7mt7SoMPRvqp2EcEhA)
[Crash Course — “Operating Systems: Memory & Processes”](https://www.youtube.com/watch?v=26QPDBe-NB8](https://intranet.hbtn.io/rltoken/VUnF6euYuzqSTjCYoxWzCQ)

https://scratch.mit.edu/
https://en.scratch-wiki.info/wiki/Motion_Blocks
https://en.scratch-wiki.info/wiki/Looks_Blocks
https://en.scratch-wiki.info/wiki/Control_Blocks
https://en.scratch-wiki.info/wiki/Events_Blocks

[Pro Git Book](https://git-scm.com/book/en/v2)
[Git Command reference](https://git-scm.com/docs)

[Getting Started with GitHub](https://docs.github.com/en/get-started)
[GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)
[Managing Merge Conflicts](https://docs.github.com/en/pull-requests/how-tos/merge-and-close-pull-requests)

[What is Version Control?](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
[Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
[GitHub Create a Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-new-repository)



Algo's
[Intro to Algorithms](https://www.geeksforgeeks.org/dsa/introduction-to-algorithms/)
[What is an Algorithm?](https://codelucky.com/algorithms/) 

Pseudocode
[A Begginers Guide to Computer Science Pseudocode](https://schmidscience.com/a-beginner-s-guide-to-computer-science-pseudocode.html)
[Pseudocode Conventions](https://peteroupc.github.io/pseudocode.html)
[Pseudocode Standard](https://users.csc.calpoly.edu/~jdalbey/SWE/pdl_std.html)

Understanding Computer Operations
[Binary Number System](https://www.tutorialspoint.com/article/binary-number-system)
[Hexadecimal Number System](https://www.tutorialspoint.com/article/hexadecimal-number-system)
[Ascii Table](https://www.asciitable.com/)


[https://www.youtube.com/watch?v=O5nskjZ_GoI](https://intranet.hbtn.io/rltoken/MuSv9jzwFo2G88KCwwzf2g) [https://www.youtube.com/watch?v=GtVDTp826DE](https://intranet.hbtn.io/rltoken/h5_Q9CkcQfy5asQfTke63w)
[https://www.youtube.com/watch?v=zltgXvg6r3k](https://intranet.hbtn.io/rltoken/_1-hl4bbRXinWkj9A-sxrw)
[https://www.youtube.com/watch?v=2mWc3YqlM7c](https://intranet.hbtn.io/rltoken/6qMprKbD9VhpmJ2xziirPw)
[https://www.youtube.com/watch?v=26QPDBe-NB8](https://intranet.hbtn.io/rltoken/VUnF6euYuzqSTjCYoxWzCQ)
[https://www.youtube.com/watch?v=26QPDBe-NB8](https://intranet.hbtn.io/rltoken/VUnF6euYuzqSTjCYoxWzCQ)

Emacs

[Beginners Guide to Emacs](https://www.masteringemacs.org/article/beginners-guide-to-emacs)
[Keyboard Macros Are Misunderstood](https://www.masteringemacs.org/article/keyboard-macros-are-misunderstood)
[Emacs Docs](https://emacsdocs.org/docs/emacs/The-Emacs-Editor)

Vi (Vimm)

[Basic Vi Commands](https://www.cs.colostate.edu/helpdocs/vi.html)

Shell Basics

[What is the shell?](https://linuxcommand.org/lc3_lts0010.php)

### C++ Tutorial

(https://www.w3schools.com/cpp/default.asp)


Assessment shit that is toooooooootally broken not even gonna try and organise it in a nice looking way.
### **ENIAC / RTFM / Encryption Quiz**


we'll see.

1. 1939 because it's when the first prototype was actually made.
2.  https://www.aps.org/archives/publications/apsnews/200208/history.cfm
3. https://www.quora.com/What-is-the-command-to-list-the-contents-of-a-directory-in-Unix-and-Unix-like-operating-systems
4. https://www.quora.com/What-is-the-ls-option-that-prints-the-author-of-a-file


5. https://unix.stackexchange.com/questions/530086/what-is-the-ls-option-to-list-entries-by-lines-instead-of-by-columns
6. https://www.quora.com/What-is-the-option-to-output-the-version-information-of-LS

### **Shell, navigation**

Sauce:

https://linuxcommand.org/lc3_lts0050.php
https://linuxcommand.org/lc3_lts0030.php
https://linuxcommand.org/lc3_lts0020.php

### **My First Web Page - HTML**

Sauce:

https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Creating_the_content
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements
https://www.w3schools.com/html/
https://docs.python.org/3/library/http.server.html
https://validator.w3.org/

### **My First Webpage - CSS

Sauce:
https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics
https://www.w3schools.com/cssref/index.php
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Flexible_box_layout/Basic_concepts
https://jigsaw.w3.org/css-validator/
https://symbl.cc/

My First Webpage JavaScript

https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Scripting
https://www.w3schools.com/js/
https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Events
https://help.disqus.com/en/articles/1717111-what-s-a-shortname

JS BEHAVIOUR

document.addEventListener("DOMContentLoaded", function(   alert("Hello!");) {
    // JavaScript code goes here
});
var thumbnailElement = document.getElementById("smart_thumbnail");
thumbnailElement.addEventListener("click", function() {
    thumbnailElement.className = (thumbnailElement.className === "small") ? "" : "small";
});
thumbnailElement.addEventListener("click", function() {
    if (thumbnailElement.className === "small") {
        thumbnailElement.className = "";
    } else {
        thumbnailElement.className = "small";
    }
});

STYLE.CSS

body {
    background-color: #f4f4f4;
    font-family: Arial, sans-serif;
  }
  h1 {
    text-align: center;
  }
  <body>
  <header></header>
  <main>
    <article></article>
    <aside></aside>
  </main>
  <footer></footer>
</body>
body {
    display: flex;
    flex-direction: column;
    margin: 0;
  }
  main {
    display: flex;
    flex-direction: row;
    flex: auto;
  }
  article {
    flex: 2;
    overflow-y: auto;
  }
  aside {
    flex: 1;
    overflow-y: auto;
  }
  @media (max-width: 768px) {
    main {
      flex-direction: column;
    }
  }
  li.logo {
    font-size: 24px;
    font-weight: bold;
  }
  Head {
    color: #2b6cb0;
  }
  p {
    color: #2b6cb0; 
  }
  h1 {
    color: #2b6cb0; 
  }


INDEX.HTML

<head>   <script src="behavior.js"></script> <meta name="viewport" content="width=device-width, initial-scale=1"> <link href="https://apply.holbertonschool.com/level2/school.css" rel="stylesheet">
    <link href="styles.css" rel="stylesheet"> </head>

    <header>     <div class="right">
        <a href="https://twitter.com/share" class="twitter-share-button" data-text="Check out my website!" data-url="https://NEKROnsAREKOOL2.com" data-hashtags="webdevelopment">Tweet</a>
        <div class="fb-share-button" data-href="https://NEKROnsAREKOOL2.com" data-layout="button"></div>
    </div>  <li class="logo">&#9733;</li> </header>
<p>This is a paragraph.</p>

<p>This is ANOTHER paragraph about Necrons</p>

<p>They like reanimate and all that cool stuff</p>

<p>guh me bomboclaat.</p>

<h1> wait what happened to the top half</h1>

<h2>This is a second-level heading</h2>

<h3>This is a third-level heading</h3>

<h4> fun is not something that likes me</h4>

<img src="https://via.placeholder.com/800" id="smart_thumbnail" class="small" alt="Thumbnail">

<main> we have fun here </main>
<aside>    <div id="disqus_thread"></div>
    <script>
    (function() {
        var d = document, s = d.createElement('script');
        s.src = 'https://@disqus_V6ViPXoaBK .disqus.com/embed.js';
        s.setAttribute('data-timestamp', +new Date());
        (d.head || d.body).appendChild(s);
    })();
    </script> </aside>
<body>    <body class="works_on_smartphone"></body>   <header>

  <nav>

    <ul>

      <li><a href="index.html">Home</a></li>

      <li><a href="about.html">About</a></li>

    </ul>

  </nav>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v12.0" nonce="abc123"></script>
</header> </body>

<p>Click the image below to learn more:</p>

<a href="https://www.holbertonschool.com">

  <img src="https://apply.holbertonschool.com/holberton-logo.png" alt="Holberton Logo">

</a>

<footer> here are more fun words </footer>


ABOUT.HTML

<title>About My Website</title>
<head>   <script src="behavior.js"></script><meta name="viewport" content="width=device-width, initial-scale=1"> <link href="https://apply.holbertonschool.com/level2/school.css" rel="stylesheet">
    <link href="styles.css" rel="stylesheet"> </head>
<header>     <div class="right">
    <a href="https://twitter.com/share" class="twitter-share-button" data-text="Check out my website!" data-url="https://NEKROnsAREKOOL2.com" data-hashtags="webdevelopment">Tweet</a>
    <div class="fb-share-button" data-href="https://NEKROnsAREKOOL2.com" data-layout="button"></div>
</div>  <li class="logo">&#9733;</li> <a href="index.html" target="_blank"></a> <a href="about.html" target="_blank"></a></header>

<body>    <header> 
    <header>    <li class="logo">&#9733;</li> </header>

    <nav>

      <ul>

        <li><a href="index.html">Home</a></li>

        <li><a href="about.html">About</a></li>

      </ul>

    </nav>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v12.0" nonce="abc123"></script>
  </header> </body>

<main> This website is used for navigation to fun topics like... :)</main>

<footer>Made by Matt_Robbo for <a href="https://apply.holbertonschool.com" target="_blank">Holberton School</footer>











](https://www.reddit.com/r/riftboundtcg/comments/1xm1yg5/riot_what_are_we_doing_here/)

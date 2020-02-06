
# Important Links
- [Class homepage](https://ledatascifi.github.io/)
- [Discussion and Announcements](https://github.com/LeDataSciFi/Discussion)
- [Lectures](https://ledatascifi.github.io/lectures-spr2020/intro.html)
- [My Participation Repo](https://github.com/jmartindyer/FIN377-participation)
- [My GH account](https://github.com/jmartindyer)

# How To
- To load my participation repo in Jupyter I run " jupyter notebook --notebook-dir "C:\Users\Juan Gabriel\Documents\GitHub\fin377-participation" "
- To commit changes to master I can *upload* a file to Github, or *commit changes* in Github desktop


| **Category** | **Rule**  |
| :--- | :--- |
| 0. **PLAN BEFORE YOU CODE** | A. "Pseudo code" is writing out the broad steps in plain language. I often (almost always for complicated tasks) do this on paper, then translate it to code as an outline (in the code's comments). <br> <br> Maybe planning sounds boring and like a waste of time. I get it; I also want to [shoot first](https://youtu.be/la7uuFsCIrg?t=43) like [Han did...](https://youtu.be/93pXrmCdlI0?t=26)  but coders like Han often [end up looking like this guy](https://youtu.be/mLyOj_QD4a4?t=67)... |
| | B. Break the problem into chunks/smaller <br>problems. This dovetails with rule 5.B below nicely. |
| 1. Automation | A. Automate everything that can be automated, don't do point-and-click analysis! |
| | B. Write a single script that executes all code from beginning to end |
| 2. Version control | A. Store code and data under version control. Revisit the [GitHub workflow recipe](01_Motivation_and_Getting_Started.html#***-THE-WORKFLOW-RECIPE--***) as needed! |
| | B. **Before checking the directory back in, clear all outputs and temp files and then run the whole directory!** (Check: Did it work right?) <br>  |
| 3.  Directories | A. Separate directories by function |
| | B. Separate files into inputs and outputs |
| | C. Make directories portable |
| 4. Keys / Units | A. Store cleaned data in tables with unique, non-missing "keys" |
| | B. Keep data normalized as far into your code pipeline as you can |
| 5. Abstraction - fncs/classes | A. Abstract to eliminate redundancy |
| | B. Abstract to improve clarity |
| | C. Otherwise, don't abstract |
| | D. **Unit test your functions!** |
| | E. Don't use magic numbers, define once as variables and refer as needed |
| 6. Documentation | A. Is good... to a point |
| | B. Don't write documentation you will not maintain |
| | C. Code is better off when it is self-documenting |
| 7. Randoms | NEVER DRAW RANDOM NUMBERS WITHOUT A SEED|

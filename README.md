# General Design Guidelines

Further explanation for the design portion of your marks.  

Every major issue I find bumps your design mark down by 1. (5 to a 4, 3 to a 2, etc.)  

Every 3 minor issues is worth 1 major issue. 

## Major Issues

- [ ] you have 5 or more confusingly-named variables and/or constants
- [ ] you don’t provide comments for things that are not obvious 
- [ ] your variable and/or constant names aren’t expressive
    - ex. `c` or `cost` vs. `costWordCents` or `costOfWordsInCents`
- [ ] you disregard explicit instructions on the assignment
    - ex. forget to prompt when asked to
- [ ] you use unreasonable variable types
    - ex. `double numKittens`
- [ ] you don’t declare your variables when you actually use them, but instead do them all “at the top of the code” and then assign values later
- [ ] you don't declare your constants at the top
- [ ] you include code that does nothing useful and/or indicates a lack of knowledge
    - ex. `double foo = (double)keyboard.nextDouble();`

## Minor Issues

- [ ] you have 2 to 4 confusingly-named variables and/or constants
- [ ] you provide **truly** unnecessary comments
    - ex. `// put numCards * 3 into variable score` or `// declare variable numKittens`
- [ ] you don’t use whitespace to separate your code into related “chunks”
- [ ] you don’t use whitespace in your expressions to space out operators, variable names, etc
    - ex. `int x=((3*y)/Math.min(4,length))+4*height` (really hard to read!)
- [ ] you use inconsistent bracing styles
- [ ] your prompts don’t have a space after them
- [ ] your prompts move the cursor to the next line (ex. you use `println()` instead of `print()` for prompts)

## Just Comments

Some things in your code might be so minor that it would be cruel to ding you on them, but I _d_o want you to be aware of them so that you can improve. Some examples:
- [ ] spelling mistakes (in comments, variables, constants)
- [ ] your prompts aren’t user friendly (“name?” instead of “Please enter your name “, for example)

For these kind of issues, I’ll put a comment in, but will not dock you marks.

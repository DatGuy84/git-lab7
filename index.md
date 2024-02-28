#Lab Report 4 - Vim

##Step 4: Log into ieng6

![Image](https://github.com/DatGuy84/git-lab7/blob/main/ssh%20ieng6.png?raw=true)

Keys pressed: ```ssh <space> storgaeide@ieng6.ucsd.edu <enter>``` ssh command allows
a local device to access a remote server, or my ieng6 account.

##Step 5: Clone my fork of the repository into my Github Account

![Image](https://github.com/DatGuy84/git-lab7/blob/main/cloning%20fork.png?raw=true)

Keys pressed: ```git <space> clone <space> <Ctrl-C> <Ctrl-V> <enter>``` git clone makes a copy
of a repository.  This command copied the forked repository of lab7 and placed it in 
my pc.

##Step 6: Run the tests to demonstrate they fail
![Image](https://github.com/DatGuy84/git-lab7/blob/main/cd%20to%20bash%20test.png?raw=true)

Keys pressed: ```cd <space> lab7-<tab> <enter> bash <space> t<tab> <enter>``` cd changes
the directory to a certain file.  This changed the directory to the cloned repository.  bash
runs the test.sh file in the cloned repository.  This runs JUNIT on the ```ListExamplesTests.java```
and utilizes tester methods to check the code of ```ListExamples.java```.  This outputs two tests
being ran and one failing.

##Step 7: Edit the code to fix the tests

![Image](https://github.com/DatGuy84/git-lab7/blob/main/vim%20ListExamples.png?raw=true)
Keys pressed: ```vim <space> L <tab> . <tab> <enter> ``` vim is a text editor that opens up
the file used as the argument.  Therefore, vim opens up ```ListExamples.java``` and allows
changes made to the file.

![Image](https://github.com/DatGuy84/git-lab7/blob/main/index%20changed.png?raw=true)

Keys pressed: ```/index1 <enter> n n n n n n n n n n e x i 2 <esc> <:wq>``` ```/``` is a vim command
that searches for the argument inputted right after it.  This allowed me to search for the first
occurrence of index1.  ```n``` is a vim shortcut that searches for the word that was searched 
before it.  This showed each occurrence of index1 and find the index1 that is causing the error.  
```e``` is another vim shortcut that goes to the end of the word.  The command went to the end of index1.
x gets rid of the character the cursor is on.  ```x ```delted the 1 of index1.  ```i``` allows vim to enter 
insert mode.  This shortcut allowed me to enter 2.  ```esc``` exited vim's insert mode.  ```:wq``` is a 
command that saves the changes to the file and quits out of vim.

##Step 8: Run the tests to demonstrate they succeed

![Image](https://github.com/DatGuy84/git-lab7/blob/main/Bash%20Success.png?raw=true)

Keys pressed: ```bash t <tab> ``` This ran the test.sh file and ran the tester files.  The
output of the file showed that ```ListExamples.java``` passed.

##Step 9: Commit and push the changes

![Image](https://github.com/DatGuy84/git-lab7/blob/main/git%20push.png?raw=true)

Keys pressed: 

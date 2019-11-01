Task 1 : Basic Task
1. Typing ls in the linux terminal displayed all the contents of my directory.
2.	The out put of entering pwd on my terminal shows the working directory.
3.	 mkdir workspace
      cd workspace
recruit@recruit-Mecer-X102:~/workspace$ 
4.	Only the newly created directory; workspace, is displayed
5.	touch README.md
6.	 cp README.md CHANGELOG.md

Notes:

Commands					Function
        mkdir					create a directory 
        cd						change directory
        touch					create a new file
        cp						coping a file and renaming it

Task 2 : Absolute and Relative Paths 
sudo mv exercise.md /temp
rm / tmp/ exercise.md

Commands					Function
       mv						move a file NB: remember to use the tab completion
       cd						change directories, relative to current location
       rm						permanently removes file from directory hierarchy  
Task 3 : cat commands

1 & 2.	
cat > umuzi.md
cat > recruits.md
cat > cohort.md

3.	 cat umuzi.md recruits.md cohort.md

4. cat umuzi.md recruits.md cohort.md > summary.md

5.	 echo "The end" >> summary.md

Commands					Function
       cat	>					creates and open file for editing
       ctrl d					closes the file
       cat						reads content of a text file

 Task 4 : The Locate command

1.	locate umuzi
2.	locate umuzi > search_result.md


Task 5 : The Locate command cont...

1.	touch pad.md
2.	cd Desktop
   mkdir work

3.	 cp "/home/recruit/Documents/"pad.md .
    mv pad.md pad_copy.md 

4.  locate updatedb
5.	 cd -
6.  locate pad_copy.md


Task 6 : find commands

1.	find -name *.pdf
2.	locate *.pdf >> files.md
3.	find . -maxdepth 1 -print


Task 7 : Text Editor

1.	nano my_bio.med
2.	Ctrl X to exist folder
3.	mkdir my_files

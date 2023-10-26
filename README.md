# 05-reading
 
Note from the video:
https://scrapism.lav.io/intro-to-the-command-line/

pwd: make sure where you are at
cd Desktop/file_name
cd: go back to the main folder
mv filename1.jpg filename2.jpg: move - used to rename file, filename1 changed into filename2
rm: delete files
open filename.jpg: open a file in it default application
cat textfilename.txt: open up a text file (print out the entire content of that text file)
manifest texfilename.txt: have a paginated text file that is able to control by up and down arrow
    q: exit the preview
grep word filename.txt: getting every line that contains word
sort filename.txt: each line sorted in alphabetic order
sort -r filename.txt: each line sorted in reversed order
sort -r -u filename.txt: each line unique sorted in reversed order
man sort: open up manual page for the sort command
ls -l: -l makes list to shownin column
ls -l -h: -h makes into human readable 
ls -a: -a show hidden files

grep Alice alice.txt > newtextfile.txt: grep the lines from Alice alice.txt and create a new file with these text(Be careful the samae name will override)
more alice2.txt: show the text in the text file
grep Alice alice.txt | sort: sorted text of alice.txt
grep Alice alice.txt | sort > sorted_alice.txt: make a new file for sorted text

up arrow will show the history that I have typed before
 hit enter will run that command again

open ali (tab): the terminal will let me tab through possible files and select the one I want

tldr li: tldr explain the function of built in things in the system


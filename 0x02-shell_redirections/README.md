This repository is used to store all the scripts for the 0x02 Alx project.
The scripts are as follows:
0. hello_world: Prints "Hello, World" using $echo
1. confused_smiley: Prints a confused smiley using $echo + \
2. hellofile: Prints contents of a "passwd" file using $cat
3. twofiles: Prints contents of 2 seperate files using $cat
4. lastlines: Prints the last ten lines of "passwd" file using $tail
5. firstlines: Prints the first 10 lines of a file using $head
6. third_line: Prints the third line of file "iacta" using $head
7. file: Creates a file containing the text "Best School" using $echo + >
8. cwd_state: Send the output of "ls -ls" command to a file called "ls_cwd_content". If the file exists the contents will be overwritten, if not then it will be created
9. duplicate_last_line: Duplicates the last line of a file using $tail -n 1
10. no_more_js: Deletes all files with the ".js" extension using $find
11. directories: Outputs the number of directories and subdirectories in the current directory using $find
12. newest_files: Lists the 10 newest files in the directory using $ls + $head
13. unique: Takes a list of words as input and prints only the words that appear once in the list using $sort + $uniq
14. findthatword: Displays all the lines containing the pattern "root" in the file "passwd" using $grep
15. countthatword: Displays the amount of lines that include the pattern "bin" in the file "passwd" using $grep
16. whatsnext: Display all lines containing the pattern "root" plusthe 3 lines following each using $grep
17. hidethisword: Displays all lines that don't contain the pattern "bin" in the file "passwd" using $grep
18. letteronly: Displays all the lines in a file that start with a letter using $grep
19. AZ: Replaces all the characters A & c from the input to X and e using $tr + $tr
20. hiago: Removes all letter c and C from the input using $tr
21. reverse: Reverses the input using $rev
22. users_and_homes: Displays all the users and their home directories using $cut + $sort

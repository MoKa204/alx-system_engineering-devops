#!/bin/bash
pwd: prints the absolute path name of the current working directory
ls: Display the contents list of your current directory
cd :changes the working directory to the user’s home directory
ls -l:Display current directory contents in a long format
ls -a: Display current directory contents, including hidden files (starting with .)
ls -n: Display current directory contents in long format with user and group IDs displayed numericall
mkdir: Creates directory
mv: move file or directory
rm: remove file
rmdir: delete directory
cd -: changes the working directory to the previous one
ls ls . .. dir:lists files in the current directory + parent + dir
file: prints the file type
ln -s: creates a symbolic link
cp -u *.html: copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory
mv [[:upper:]]*: moves all files beginning wth an uppercase letter
rm *~: delete all files ending with ~
mkdir -p dir/dir1/dir2/...: creating recursive directories
ls -amp: lists all files separated with commas, ending with/
file -C -m: compiling a magic file

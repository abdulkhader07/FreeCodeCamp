# FreeCodeCamp
learning new tech

# All about terminal

## Saying hello :
```terminal
echo hello terminal 
echo text # file name
```
#eg : echo I made this boilerplate >> README.md

## To check the path:
```terminal
pwd    
```

## To check whats there in the folder:
```terminal
ls
```
-ls stand for list

## To change the directory in a folder:
```terminal
cd <folder_name>
```
#cd stands for change directory
#eg : cd freeCodeCamp

## Colour code for folders and files:
1. for folders : blue
2. for files   : include their extension
3. for images  : pink (jpg, png, jpeg ,svg etc)
4. for font    : basic black 

```diff
@@Remember folder and directory are same thing@@
```

## To go back one level of directory:
```terminal
cd ..
```

## To see whats there in a file :
```terminal
more <filename>
```
#eg : more package.json 

# To clear the terminal
-> clear

# To flag a folder's file:
-> ls <flag>
#eg : ls -l
#eg : ls --help

# To go back two levels of directory:
-> cd ../..
#here you are using / for multiple levels

# To make a new folder :
-> mkdir <folder_name>
#mkdir stands for make new directory

# To print something :
-> echo <something>
#eg : echo hello website

# To create a new file in a folder:
-> touch <somthing>
#eg : touch index.html
#eg : touch client/assets/fonts/roboto-bold.woff

# To turn the folder into a git repository:
-> create a file by (touch .gitignore) in the folder


# To list out all the file in a repository:
because .gitignore file is hidden to see it we will use --all cmd
-> ls --all
   or
-> ls -a

# To copy the file to another folder:
-> cp <file_name> <folder_name>
#eg : cp background.jpg images

# To remove a file :
-> rm <file_name>
#eg : rm background.jpg

# To move or change the extension:
-> mv <filename> <new_filename>
#eg : mv photos/footer.jpeg client/assets/images

# To find things or view a file tree:
-> find
-> find <folder_name>
-> find -name <file_name>
#eg : find client
#eg : find -name index.html
#eg : find client/assets/fonts

# To create a folder from outside:
-> mkdir <>/<>
#eg : mkdir client/src

# To remove the directory:
-> rmdir <directory_name>

# To remove files and directoy togeather:
-> rm -r <folder_name>
# -r stands for recursive flag

# To exit the terminal :
-> exit




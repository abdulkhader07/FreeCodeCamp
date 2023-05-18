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

## To clear the terminal
```terminal
clear
```

## To flag a folder's file:
```terminal
ls <flag>
```
#eg : ls -l <br>
#eg : ls --help

## To go back two levels of directory:
```terminal
cd ../..
```
#here you are using / for multiple levels

## To make a new folder :
```terminal
mkdir <folder_name>
```
#mkdir stands for make new directory

## To print something :
```terminal
echo <something>
```
#eg : echo hello website

## To create a new file in a folder:
```terminal
touch <somthing>
```
#eg : touch index.html <br>
#eg : touch client/assets/fonts/roboto-bold.woff

## To turn the folder into a git repository:
```terminal
create a file by (touch .gitignore) in the folder
```

## To list out all the file in a repository: <br>
because .gitignore file is hidden to see it we will use --all cmd
```terminal
ls --all
```
   or
```terminal
-> ls -a
```

## To copy the file to another folder:
```terminal
cp <file_name> <folder_name>
```
#eg : cp background.jpg images

## To remove a file :
```terminal
rm <file_name>
```
#eg : rm background.jpg

## To move or change the extension:
```terminal
mv <filename> <new_filename>
```
#eg : mv photos/footer.jpeg client/assets/images

## To find things or view a file tree:
```terminal
find
find <folder_name>
find -name <file_name>
```
#eg : find client <br>
#eg : find -name index.html <br>
#eg : find client/assets/fonts <br>

## To create a folder from outside:
```terminal
mkdir <>/<>
```
#eg : mkdir client/src

## To remove the directory:
```terminal
rmdir <directory_name>
```

## To remove files and directoy togeather:
```terminal
rm -r <folder_name>
```
# -r stands for recursive flag

## To exit the terminal :
```terminal
exit
```




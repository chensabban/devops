# devops homeworks

## create directories and files

create directories dir1, dir2, dir3 within homework directory
'''bash
mkdir homework
mkdir dir1 dir2 dir3

cd dir1
touch file1.txt file2.txt file3.txt
'''

## add content to files
'''bash
echo hello world > file1.txt
echo hello world > file2.txt
echo hello world > file3.txt
echo hi my name is chen >> file1.txt   
'''

## using grep and find commands
'''bash
grep hel* file1.txt
grep h* file1.txt                      
cat file1.txt | grep h*
cat file1.txt | grep 'hi'

find -name "*.txt"
find -mtime -7
'''

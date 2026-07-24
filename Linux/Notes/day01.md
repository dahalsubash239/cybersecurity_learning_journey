Learned Commands :
cd - change the current working Directory
mkdir - make directory 
ls - list file and directory present in working directory 
pwd - full path of current directory 
rmdir - remove directory 
cat - display file content 
cp - copy files or directories
mv - move or rename files or directory
rm - remove file 
uname - display system information 
locate - find files using Database 
touch - create empty file 
echo - create file with content (> overwrite, >> append)
ln - create link between files 

Info:
  softlink:
    A symbolic link is a pointer to the original file path. If you delete the original file, the link breaks.
    Can link across different filesystems.
    Can link to directories.
    Breaks if original file is moved
    -f flag to create it
    Ex: ln -f subash.txt subas.txt
  HardLink
    Cannot link across different filesystems.
    Cannot link to directories.
    Stops working only if all links are deleted
    Ex: ln  subash.txt subas.txt

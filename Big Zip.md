# Big Zip - PicoCTF (Beginner)
## Unzip this archive and find the flag. (Easy, General Skills)

### 1) Download the file
I downloaded the zip folder from the website  

### Mistake - Searched for the flag without narrowing down the directory to the new folder 
grep "pico"  

### 2) Find the file and move to that directory
find "big-zip-files.zip"  
find "downloads"  
cd downloads  

### 3) Unzip the file
unzip big-zip-files.zip  
sudo apt install unzip  
unzip big-zip-files.zip  

### 4) Find the flag using grep
grep pico  
cd big-zip-files  
grep "pico"  

### it took a long time because the folder had loads of files for grep to search through, but after a while it returned the flag in the format "picoCTF{example_flag}"
### apologies i lost the actual flag that i got and i deleted the folder now but i got it just trust me pls lol

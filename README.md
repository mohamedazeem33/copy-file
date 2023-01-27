# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
```
#Step 1:
Get the file name and location from the user.
#Step 2:
Give a new file name to create a copy of a file content.
#Step 3:
Read the file and close the file.
#Step 4:
Now write the content in the new file.
#Step 5:
When done print "File copied successfully".
#Step 6:
End of the program
```
## PROGRAM:
```python
#Program For Copying The Contents:
#Developed by:  MOHAMED AZEEM N
#RegisterNumber: 22007405
print("Enter the Name of Source File: ")
sFile = input()
print("Enter the Name of Target File: ")
tFile = input()
fileHandle = open(sFile, "r")
texts = fileHandle.readlines()
fileHandle.close()
fileHandle = open(tFile, "w")
for s in texts:
 fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!"
```

### OUTPUT:

![program](https://user-images.githubusercontent.com/121040764/215116543-3ee23080-93ef-4036-a49b-578e72c3be54.jpg)

![Screenshot (38) new](https://user-images.githubusercontent.com/121040764/215127481-ea60153e-21b3-4e9c-b7ca-6349bc7ea81c.png)


![Screenshot (39) new](https://user-images.githubusercontent.com/121040764/215127522-bda4e96d-1d51-4ccc-98d4-4f835bbf36a2.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.

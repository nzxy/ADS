# Application Digital Signature
Crude batch script that will remotely connect to a computer’s c$ admin share and check a specified applications file version. This is my first published bash script.

## The program

 **The Script runs inside a program that allows users to complete three tasks:**

1. Count to 2000 and back

2. Report on a specified applications digitals signature using Sigcheck

3. Exits the program

## ADS Batch Script Details
- Computers must be on the same domain and a text file must be made to specify which computers 
  to run sigcheck on. Put the file in active directory and run the script as administrator.
- The script determines whether the computer is up or down by pinging and reporting its status. 
- The script creates a log in the C: folder under ADSlogs.
- Replace the executable and log file directories to report on other applications. 
  The default application is Quicktime. 

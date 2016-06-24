# ADS
Application Digital Signature

ADS BATCH SCRIPT:
1. Counts to 2000 and back.
2. Reports a specified applications digital signature information using Sigcheck.

	Computers must be on the same domain and a text file must be made to specify which computers 
	 to run sigcheck on. Put the file in active directory and run the script as administrator.
       - The script determines whether the computer is up or down by pinging and reporting its status. 
       - The script creates a log in the C: folder under ADSlogs.
       - Replace the executable and log file directories to report on other applications. 
         The default application is Quicktime. 
 
3. Exits the script.

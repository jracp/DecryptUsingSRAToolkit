# Decryption Using SRA Toolkit
This is a step-by-step manual for decrypting the encrypted genome data files using [SRA Toolkit](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=software) in [macOS Mojave 10.14.4](https://support.apple.com/kb/DL1994) for beginners.

## Requirements
Here is a list of requirements:
 - Having administrative privileges
 - Accessing terminal
 - Internet connection
 
## Step 0
Download data files and they decryption key

## Step 1
Download SRA Toolkit from [HERE](https://trace.ncbi.nlm.nih.gov/Traces/sra/sra.cgi?view=software) and uncompress by double click on the downloaded archive

## Step 2
Open terminal using either (Ctrl + Alt + t) or *Search* and type in **terminal** and then hit *Enter* and go to /User/[username]/Downloads/sratoolkit.2.9.6-mac64/bin/

**Note**: Replace [username] with your username, e.g. mike, throughout this manual

## Step 3
Type in ```./vdb-config -i``` and hit *Enter*

## Step 4
Hit *4* and navigate to the folder where the key is stored and hit *OK*

## Step 5
vdb-config prompts if you want to import the key, hit *OK*

## Step 6
Next, it will ask you if you want to change the directory, hit *NO*

## Step 7
Now hit *6* to save changes, *OK* and then *7*

## Step 8
Now copy all data files download in ##Step 1 to ```/Users/[username]/ncbi/[dbGaP-#####]/files/```

## Step 9
Go back to terminal and navigate to ```/Users/[username]/ncbi/[dbGaP-#####]/files/```

## Step 10
Now type in ```/Users/[username]/Downloads/sratoolkit.2.9.6-mac64/bin/vdb-decrypt /Users/[Username]/ncbi/dbGaP-21073/files/[filename].ncbi_enc``` and hit *Enter*

**Note**: Replace [filename] with the actual file name

## Step 11
The decrypted compressed file will be stored in the same directory

## Step 12
Uncompress the decrypted file to see the actual file

# More info
Check the following reference for further information
 - [Decrypting and Extracting Data](https://www.ncbi.nlm.nih.gov/books/NBK63512/#Download.i_used_the_vdb_tools_to_work_on)
 - [Installing OpenJDK on Debian-based systems]

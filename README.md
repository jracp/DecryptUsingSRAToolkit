# DecryptUsingSRAToolkit
Decrypt the encrypted genome data files using SRA Toolkit


Decrypt the encrypted files using SRA Toolkit


1- Download data files
2- Download the key
3- Download SRA Toolkit from
4- Uncompress the files into a arbitrary directory
5- Open terminal and go to sratoolkit.2.9.6-mac64/bin/
6- Type in ./vdb-config -i and hit Enter
7- Hit 4 and navigate to the folder which the key is stored and hit OK
8- vdb-config prompts if you want to import the key, hit OK
9- Next, it will ask you if you want to change the directory, hit NO
10- Now hit 6, OK and then 7
11- Now copy all data files that download in (1) to /Users/[Username]/ncbi/[dbGaP-#####]/files/
12- Go back to terminal and navigate to /Users/[Username]/ncbi/[dbGaP-#####]/files/
13- Now type in /Users/[Username]/Downloads/sratoolkit.2.9.6-mac64/bin/vdb-decrypt /Users/[Username]/ncbi/dbGaP-21073/files/[filename].ncbi_enc and hit Enter
14- The decrypted compressed file will be stored in the same directory
15- Uncompress the decrypted file to see the actual file

                            **Modification needed before usage**

Copy the Asprvm8s.bin into a folder you want , then use text editor to modify this part of the script


lab78_1:
log VMcodeloc
lm VMcodeloc, 4000, "d:\Asprvm8s.bin"         ---> modify this line


if Asprvm8s.bin is copied under the folder c:\script the above command should be chnaged as


lm VMcodeloc, 4000, "C:\script\Asprvm8s.bin"




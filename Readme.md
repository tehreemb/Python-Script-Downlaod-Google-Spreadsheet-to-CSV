1.) Edit GoogleDocDownload.py with Google username & passqword that has permissions to the Google Spreadsheet and the spreadsheet key

Edit the following parts of the code
email = "enteryourgmail@gmailaddresshere.com" # (your email here)
password = "enteryourpasswordhere" #(your password here)
spreadsheet_id = "11lwiE4SaHriLSjFgVaGSuOc8-zY5Lb-0Q9O_pNxtESc" # (spreadsheet id here)

2.) pip install py2exe

3.) Run this from command line

python setup.py py2exe

4.) It will create an EXE file in a folder called Dist Rename the .EXE to .COM so SSIS picks it up

5.) Create an 'Execute process' task in SSIS and point it to the .COM file
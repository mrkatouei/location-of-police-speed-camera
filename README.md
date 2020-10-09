# Police-Speed-Camera-Location
 #written by mohamadreza-katoueizade from persia
No longer fucntional as the data is no longer published.

Downloads and parses a web download with the speed camera locations

Get_Locations:
To Run, "python3 Get_Locations.py"
Will print error if the pdf hasn't been uploaded by the police yet for the week. It isn't an issue for me as I use crontab to run it on sunday Essentailly auto run for linux
Uses these imports; date time, re, glob, os, requests, dateutil.
Only Ran on Linux
Must have pdf to text also.

Send_Today_To:
Have to add your own gmail details as its described in the comment in the code. And add a target email in the send_to file.


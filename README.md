# SocketProgramming_File-Transfer
This program helps to transfer file from server to client using socket programming.




## Requirements: 

  - python2
  - socket

 
## How to run?
if you are sender copy your files to dir and run:
set your file name in sender.ipynb first `


if you are receiver you have 2 options:

-  1- Simply recv the file with orginal format
-  2- Recv the file with converted format

if you choose 1 then
ask your sender to tell you orginal format and set it to receiver.py:
python
recv_file = open('anyName.askYourServerToTellYourFormat','wb')

and
terminal
python receiver.py

but if you choose 2:
python
recv_file = open('anyName.yourformat','wb')

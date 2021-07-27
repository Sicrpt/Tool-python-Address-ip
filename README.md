# Tool-python-Address-ip
#Hussen Mhommed 
#H . M . A
from __future__ import absolute_import
from __future__ import print_function
import socket
from six.moves import input
from colorama import Fore 
Red=Fore.RED

print(Red+"PY @Sicrpt")

logo = (""" _   _____  
| | |  _  \ 
| | | |_| | 
| | |  ___/ 
| | | |     
|_| |_|     """)
print (logo)

hostname = input (" Enter title site :")
addr = socket.gethostbyname (hostname)
print(("الهدف {} Address  {}".format (hostname, addr )))


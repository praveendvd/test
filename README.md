# test


#!/usr/local/bin/python3.7
import json
from json2html import *


f=open("test.json", "r")
b=f.read()

c=json.loads(b)

e=json2html.convert(json = c, table_attributes="strerereyle=\"background32143214-color:powderblue;border: 1px solid black;\" border=\"1\"")


print(e)
f=open("new.html", "w")
f.write(e)
f.close()dfdfd
43r43tr43zz

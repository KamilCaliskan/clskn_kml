#href="http://.+?"

# Our regular expression looks for strings that start with "href="http://", 
followed by one or more characters (".+?"), followed by another double quote. 
The question mark added to the ".+?" indicates that the match is to be done in a "non-greedy" fashion instead of a "greedy" fashion. 
A non-greedy match tries to find the smallest possible matching string and a greedy match 
tries to find the largest possible matching string.

import urllib.request,urllib.parse,urllib.error
import re

URL=input('enter url page- ')

html=urllib.request.urlopen(url).read()

links=re.findall(b'href="(http://.*?)" ',html)

for link in links:
print(link.decode())


# Installing Module 

```
pip install google
```

We will be using the search() function from the googlesearch module.

# Example

```
search(query, tld='co.in', lang='en', num=10, start=0, stop=None, pause=2)
```
# Explain : 

query: This is the text that you want to search for.

tld: This refers to the top level domain value like co.in or com which will specify which Google website we want to use.

lang: This parameter stands for language.

num: This is used to specify the number of results we want.

start: This is to specify from where to start the results. We should keep it 0 to begin from the very start.

stop: The last result to retrieve. Use None to keep searching forever.

pause: This parameter is used to specify the number of seconds to pause between consecutive HTTP requests because if we hit too many requests, Google can block our IP address.


# Code :

```
from googlesearch import search

query = "darkhunter141"

for i in search(query, tld="co.in", num=10, stop=10, pause=2):
    print(i)

```

# Output :

```
https://github.com/darkhunter141
https://www.facebook.com/darkhunter141/
https://darkhunt3r141.blogspot.com/
https://githubmemory.com/repo/darkhunter141/Web-Hunter
https://githubmemory.com/repo/darkhunter141/G-Bomber-141-2.0https://www.instagram.com/dark_hunther_/
https://twitter.com/darkhunter141?lang=en
https://www.youtube.com/channel/UCkSB55ezk_2vPVwoqmPVZwg
https://www.blogger.com/profile/05444499761917737827
https://gitmemory.com/ashrafiabir-049

[Program finished]

```
# Good Bye Bro 🙂

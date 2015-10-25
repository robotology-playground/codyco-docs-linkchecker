# codyco-docs-linkchecker
Script for checking broken links in website and documentation of the CoDyCo EU project. 

# Use 

## Install LinkChecker 
We use the [LinkChecker](http://wummel.github.io/linkchecker/) tool to check for broken links in our websites, you can install it throught 
[pip](https://docs.python.org/2/installing/) (only on Python 2, Python 3 not supported at the moment):
~~~
pip install LinkChecker 
~~~

## Check for broken links 
For checking for broken links in the [www.codyco.eu](www.codyco.eu) website, use this command in the root of this repo:
~~~
linkchecker -f codyco-linkcheckerrc --check-extern www.codyco.eu
~~~
for checking broken links on [wiki.icub.org/codyco](http://wiki.icub.org/codyco), use instead:
~~~
linkchecker -f codyco-linkcheckerrc --check-extern http://wiki.icub.org/codyco
~~~

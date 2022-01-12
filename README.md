# Technical-Blog
Writing technical blog to remember the issue that I met and solved.

Blog 2022-1-12
issue:cant push the code from pycharm to github.
solve:
https://www.cnblogs.com/yanch01/p/GitHub-access.html
use this link to connect github from China without the ladder.

69.171.224.40 github.global.ssl.fastly.net
185.199.111.153 assets-cdn.github.com
140.82.113.4 github.com
140.82.113.4 www.github.com
add these four lines to my host file,path is c:/windows/system32/driver/etc/host(file)

https://stackoverflow.com/questions/18356502/github-failed-to-connect-to-github-443-windows-failed-to-connect-to-github
use this link to change proxy.the answer is:

*************************************
If your git was already set to something and you only copied that folder to some other location, simply run:
git config --global http.proxy ""
And git will set itself straight, after what, you can pull again :)
*************************************

Done.

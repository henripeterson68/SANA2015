# SANA2015
SANA 2015 Quiz for training purpose

There is a new tool called GitHub HTML Preview, which does exactly what you want. Just prepend http://htmlpreview.github.io/? to the URL of any HTML file, e.g. http://htmlpreview.github.io/?https://github.com/twbs/bootstrap/blob/gh-pages/2.3.2/index.html

Note: This tool is actually a github.io page and is not affiliated with github as a company.
Example: 
http://htmlpreview.github.io/?https://github.com/henripeterson68/SANA2015/blob/main/Quiz_SANA2015_2.html

http://htmlpreview.github.io/?https://github.com/henripeterson68/SANA2015/blob/main/Quiz_SANA2015_1.html

Development CDN GitHack:
https://raw.githack.com/henripeterson68/SANA2015/main/Quiz_SANA2015_2.html

Production GitHack:

https://rawcdn.githack.com/henripeterson68/SANA2015/2cb6f8966fefe62089e052b83dc2f5c9ac6e91a6/Quiz_SANA2015_2.html?min=1

CDN GitHack:
https://rawcdn.githack.com/henripeterson68/SANA2015/V1.0.0.0/Quiz_SANA2015_3.html?min=1

CDN cdn.jsdelivr.net:
JSDelivr has a nice integration with GitHub. The following raw GitHub url

https://raw.githubusercontent.com/usystems/webling-plugins/main/examples/member-map/index.js

can be accessed through the JSDelivr by

https://cdn.jsdelivr.net/gh/usystems/webling-plugins@latest/examples/member-map/index.js

How does it work
Replace http://raw.githubusercontent.com/ with https://cdn.jsdelivr.net/gh/. Make sure you don’t forget the /gh/ segment.
Remove «main» from the url, because JSDelivr always takes the file from the main branch.
Add a GitHub tag after the repository. Either a tag from GitHub like 1.0.0 or latest for the latest version of this file.
If you don’t add the latest tag, JSDelivr will cache your file and always deliver the same file.

Forgetting to add the latest tag to your url, JSDelivr will update to a new version after some time. After committing a new version it may take some time until JSDelivr updates its caches.

https://github.com/henripeterson68/SANA2015/V1.0.0.0/Quiz_SANA2015_3.html

https://cdn.jsdelivr.net/gh/henripeterson68/SANA2015@V1.0.0.0/Quiz_SANA2015_3.html?content-type=application/javascript


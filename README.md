#Workshop - Using the Dev Tools

In this exercise we will be using the dev tools in Google chrome. Although there are excellent dev tools also available in Firefox and Safari, we have chosen to use Chrome due to its ease of use and clarity of information.

##A GET request to a URL
* Visit http://www.ebuyer.com
* Open the network tab and look for the request named 'www.ebuyer.com'
* Can you find the response status code of this request? 
  * What does is the meaning of this status code?
  * List some resources you could use to look up the meaning of other status codes you may come across.
* What language is listed as acceptable in the request headers?
  * what is the purpose of this header? Why might this information be useful?
* Name a URL that is listed in the content-security-policy.
  * what is this list of URLs for? 
* What was the total response time of the request?
* Look for meta data in the HTML response - what is the "description" tag for?

##POSTing form data
* Visit https://online.lloydsbank.co.uk/personal/logon
* Open the network tab of your dev tools
* Enter a fake name and password (not a password you normally use)
* Open the 'primaryLogin' request
  * Can your pair partner find what fake password you entered on the site?
  * What can you infer from this about the behaviour of forms on websites?


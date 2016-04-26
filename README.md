#Workshop - Using the Dev Tools

In this exercise we will be using the dev tools in Google chrome. Although there are excellent dev tools also available in Firefox and Safari, we have chosen to use Chrome due to its ease of use and clarity of information.
ebuyer

Visit http://www.ebuyer.com
Open the network tab and look for the request named 'www.ebuyer.com'
* Can you find the response status code of this request?
  200
* What does is the meaning of this status code?
  It means 'OK'
* List some resources you could use to look up the meaning of other status codes you may come across.
  Google
  https://developer.mozilla.org/en-US/docs/Web/HTTP/Response_codes
* What language is listed as acceptable in the request headers?
  en,zh-CN;q=0.8,zh;q=0.6,en-US;q=0.4
  Accept:text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
  Accept-Language:en,zh-CN;q=0.8,zh;q=0.6,en-US;q=0.4
* what is the purpose of this header? Why might this information be useful?
  It will provide useful information about the client that the server can use to deal with the request, perhaps spoken language meta data that will be used to present the correct version of the body
* Name a URL that is listed in the content-security-policy.
  www.googleadservices.com
* what is this list of URLs for?
  Content Security Policy (CSP) is a computer security standard introduced to prevent cross-site scripting (XSS), clickjacking and other code injection attacks resulting from execution of malicious content in the trusted web page context.[1] It is a Candidate Recommendation of the W3C working group on Web Application Security,[2] widely supported by the modern web browsers.[3] CSP provides a standard method for website owners to declare approved origins of content that browsers should be allowed to load on that website — covered types are JavaScript, CSS, HTML frames, web workers, fonts, images, embeddable objects such as Java applets, ActiveX, audio and video files, and other HTML5 features.
* What was the total response time of the request?
  The request was sent in 0.16 ms to ebuyer.com

* Look for meta data in the HTML response - what is the "description" tag for?
  It provides a description of the page content


Visit https://online.lloydsbank.co.uk/personal/logon
* Open the network tab of your dev tools
* Enter a fake name and password (not a password you normally use)
* Open the 'primaryLogin' request
* Can your pair partner find what fake password you entered on the site?
  frmLogin:strCustomerLogin_userID:meetyourmakers
  frmLogin:strCustomerLogin_pwd:whatevrer
* What can you infer from this about the behaviour of forms on websites?
  They submit POST requests that include the information you provided in the form



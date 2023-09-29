[Go back to Web](https://github.com/leonardo-cabral67/today_i_learned/tree/main/web)

[Go back to README](https://github.com/leonardo-cabral67/today_i_learned/tree/main)

### CGI

(Common gateway interface)

In the beggining of the internet, all pages were served of a static way, using only `HTML`. Pages needed a server to ouput html in a client (browser), after a while CGI was invented, and in a simple way, instead of just take `HTML` files, server could now run executable files (Which return `TEXT/HTML`) and output TEXT/HTML output to the client. Then, it could be possible receive params and return dynamic content to the browser.
A good example of this are formularys, where you send data by param to the server, CGI receive this params, execute the script and return text/HTML, then the new content is servered to the client.

This is a concept that people who get started in web development with Javascript may not know about because Js runs natively in the client side (browser), and it doesn't need a web server and CGI to "parse" the script.

Here is an image that may help to understand better this concept:

![image showing how CGI works](https://www.oreilly.com/openbook/cgi/figs/cgi0101.gif "how CGI works")

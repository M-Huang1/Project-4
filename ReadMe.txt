Project 4
Marshall White and Zhao Huang

For project 4, our high level approach was to use sockets to send API requests to the fakebook server and
the HTMLParser libary to handle parsing the html code that the sockets returned. We used Http/1.1 for both
the POST and GET requests and added all the necessary headers such as host, length, encoding and etc.
One major roadblock in the project was finding the cookies and recreating the html forms to log into fakebook.
We solved the problem by using the developer tools provided by firefox which provided clear API history
and was instrumental to creating the correct post form to log in. The webcrawler itself was simply an iterative loop
of the hyperlinks provided by the fakebook homepage.
We tested our code by running it against the fakebook server and finding the 5 secret flags.
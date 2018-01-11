# EasyHTTP Library
	EasyHTTP is a simple Object Oriented JavaScript library for using the XMLHttpRequest API. Just pass easyHTTP a URL and callback function, no need to worry about setRequestHeader(), onload(), send(), etc..

**Steps**
---------

**Download or Pull This Repo**
	Once downloaded, add easyhttp.js to your project folder. Or use this project as a starting point for your project.

 **Instantiate easyhttp.js In Your Project**
		const http = new easyHTTP;

 **Send GET, POST, PUT, and DELETE Requests**
		// GET a single post example
		http.get('http://jsonplaceholder.typicode.com/posts/1',
			function(err, post) {
				if(err) {
					console.log(err)
				} else {
					console.log(post);
				}
			});

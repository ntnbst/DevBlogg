# DevBlogg
A Blog posting site, Where you are allowed to 
* Post
* Edit 
* Delete 

Name  | Path      | HTTP Verb | Purpose           | Mongoose Method 
---   | ---       | ---       | ---               |--- 
Index | /blogs     | GET       | List all blogs     | Blog.find() 
New	  | /blogs/new	| GET	      | Show new blog form	| N/A
Create| /blogs	    | POST	    | Create a new blog, then redirect somewhere| Blog.create()
Show	|/blogs/:id	| GET	      | Show info about one specific blog | Blog.findById()
Edit	|/blogs/:id/edit|	GET	  |Show edit form for one blog| Blog.findById()
Update|/blogs/:id	|PUT	      |Update particular blog, then redirect somewhere| Blog.findByIdAndUpdate()
Destroy|/blogs/:id |DELETE	    |Delete a particular blog, then redirect somewhere| Blog.findByIdAndRemove()


Followed RESTFUL Convention to build this site
All seven ROUTES are covered, some are these : 

## INDEX ROUTE
![Index](https://github.com/ntnbst/DevBlogg/blob/master/screenshots/index.jpg)

## NEW ROUTE
![New](https://github.com/ntnbst/DevBlogg/blob/master/screenshots/new.jpg)

## SHOW ROUTE
![New](https://github.com/ntnbst/DevBlogg/blob/master/screenshots/show.jpg)

## EDIT ROUTE
![New](https://github.com/ntnbst/DevBlogg/blob/master/screenshots/edit.jpg)


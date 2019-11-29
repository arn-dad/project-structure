## API implementation

create class for each endpoint 

`PEOPLE`
Get people list       : [GET]  : https://it-blog-posts.herokuapp.com/api/people
Get By Id             : [GET]  : https://it-blog-posts.herokuapp.com/api/people/{id}
Log in                : [POST] : https://it-blog-posts.herokuapp.com/api/people/login
Create (registration) : [POST] : https://it-blog-posts.herokuapp.com/api/people

`POSTS`
[GET]: https://it-blog-posts.herokuapp.com/api/posts


Structure

  -index.js [API class]
  -people.js [peope endpoint class]
  -posts.js [posts endpoint class]

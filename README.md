# endpoints-example
> an example api written using endpoints

# Setup Instructions

1. Clone repo
2. `npm install`
3. `npm start`
4. Open browser to (for example):
  - [https://jsonapi-example.herokuapp.com](https://jsonapi-example.herokuapp.com)
  - [https://jsonapi-example.herokuapp.com/v1](https://jsonapi-example.herokuapp.com/v1)
  - [https://jsonapi-example.herokuapp.com/v1/authors](https://jsonapi-example.herokuapp.com/v1/authors)
  - [https://jsonapi-example.herokuapp.com/v1/authors/1](https://jsonapi-example.herokuapp.com/v1/authors/1)
  - [https://jsonapi-example.herokuapp.com/v1/authors/?filter[id]=1,2](https://jsonapi-example.herokuapp.com/v1/authors/?filter[id]=1,2)
  - [https://jsonapi-example.herokuapp.com/v1/authors?include=books](https://jsonapi-example.herokuapp.com/v1/authors?include=books)
  - [https://jsonapi-example.herokuapp.com/v1/authors?filter[alive]=true](https://jsonapi-example.herokuapp.com/v1/authors?filter[alive]=true)
  - [https://jsonapi-example.herokuapp.com/v1/authors?filter[dead]=true](https://jsonapi-example.herokuapp.com/v1/authors?filter[dead]=true)
  - [https://jsonapi-example.herokuapp.com/v1/books?include=chapters,author](https://jsonapi-example.herokuapp.com/v1/books?include=chapters,author)
  - [https://jsonapi-example.herokuapp.com/v1/books?include=first_chapter](https://jsonapi-example.herokuapp.com/v1/books?include=first_chapter)
  - [https://jsonapi-example.herokuapp.com/v1/books?filter[published_before]=1990-01-01](https://jsonapi-example.herokuapp.com/v1/books?filter[published_before]=1990-01-01)
  - [https://jsonapi-example.herokuapp.com/v1/books?filter[published_after]=1990-01-01](https://jsonapi-example.herokuapp.com/v1/books?filter[published_after]=1990-01-01)
  - [https://jsonapi-example.herokuapp.com/v1/chapters?filter[id]=1](https://jsonapi-example.herokuapp.com/v1/chapters?filter[id]=1)
  - [https://jsonapi-example.herokuapp.com/v1/chapters/1](https://jsonapi-example.herokuapp.com/v1/chapters/1)

For more details on how to interact with this API, see the [JSON-API Specification](http://jsonapi.org)

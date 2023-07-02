# Starter-GraphQL-Spring-Java
Example for GraphQL in Java

`query AllBooks {
  allBooks {
    id
    title
    pages
  }
}`

`mutation UpdateBook {
  updateBook (
    id : 1
    title : "test"
    pages : 999
  ) {
    id
    title
    pages
  }
}`

`mutation createBook {
  createBook (
    title : "test"
    pages : 2222
  ) {
    id
    title
    pages
  }
}`

`mutation DeleteBook {
  deleteBook (
    id : 3
  ) {
  	message
  }
}`

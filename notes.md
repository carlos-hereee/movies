steps:

1. git status
2. mkdir folderName
3. cd folderName
4. git init 
5. npm init -y
6. code .
7. `npm i nodemon -D` <- install nodemon as a development time dependency 
8. `npx gitignore node`

endpoint ( url + http method) === function

POST /api/movies (body: movie) === postApiMovies(movie)

|non REST | REST |
|: -- |: --: |
|/createMovie|POST /api/movies |
|/removeMovie/:id | DELETE /api/movies/:id | 

Other approaches to building Web Api 

- GraphQL
- gRPC
- RPC
- SOAP
-
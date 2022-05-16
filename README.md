# Blockchain-Golang

# 1- Run
go run main.go

# 2- Create
Postman POST
http://localhost:3000/new
body
raw
json

{ "title":"",
  "author":"",
  "isbn":"",
  "publish_date":""
}

# 3- Control
Postman POST
http://localhost:3000
body
raw 
json

{
 "book_id": "b2bf5ec0004762984a4003d24292a5aa",
 "user": "furkan",
 "checkout_date": "2022-05-16"
}

# 4- All
Postman GET
http://localhost:3000

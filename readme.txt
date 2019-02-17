[POST] /auth/login json { "username" : "admin", "password" : "Admin123$"}

[GET] /book

[POST] /book/create json { "title" : "x", "author" : "xx"}

[PUT] /book/update/:id json { "title" : "y", "author" : "yy"}

[GET] /book/detail/:id

[DELETE] /book/delete/:id

[POST] /auth/logout
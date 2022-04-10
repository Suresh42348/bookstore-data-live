//page1

list of all categories=>localhost:9800/category
list of all books=> localhost:9800/books



//page2
list of books based categoryid=> localhost:9800/books/categoryid=1
list of books based on bookid=> localhost:9800/books/bookid=1



details of books based on bookid or category id
localhost:9800/details?categoryid=1
localhost:9800/details?bookid=1


Filter on basis of date of book launch=>
Filter on basis of price Low to High=>
Filter on basis of price High to Low=>
sorting(letter: A-Z)=>
sorting(letter: a-z)=>


//page3
Place Order (post)=> localhost:9700/placeOrder (body) > { "name":"suresh", "email":"suresh@gmail.com", "address":"Hno 23,Sector 1", "phone":945645656, "cost":600, "bookid":[4,6,7], "status":"Pending" }



//page4
See all order place=>
localhost:9700/viewOrder Get Order on basis of emailId
localhost:9700/viewOrder?email=suresh@gmail.com


//page5
update order (put)=> localhost:9700/updateOrder/6251a39a151064904127bc2c (body) { "status":"In Transit", "bankName":"Axis Bank" }



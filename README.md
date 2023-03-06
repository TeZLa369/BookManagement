
## BookManagement
This app is for book record management

## Endpoints:
POST: new user
GET: list of users

## /users/(id)
GET: user by ID
PUT: update user by ID
DELETE: delete user by ID (check if the user has an issued book && is there any fine to be collected from the user)

## /users/subscription-details/(id)
GET: user subs details
1. Date of Subs
2. Valid til??
3. Fine, if any?

## /books
GET: get all books
POST: Add a new book

## /books(id)
GET: Book by ID
POST: Udpt book by ID

## /books/issued
GET: Books issued here

## /books/issued/withfine
GET: All books issued with fine

## subs type
Basic: 1 month
Standard: 6 month
Premium: 12 month

If user has an issued book and it has to be returned at 10-10-2023
If it missed the return date then have to pay fine of Rs. 50/-


If user has an issued book and it has to be returned at 10-10-2023
If it missed the return date && the user's subs is also expired then user have to pay Rs. 150/- (50+100)


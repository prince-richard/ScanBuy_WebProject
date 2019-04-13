# ScanBuy_WebProject
As a user of ScanBook, I would like to be able to easily enter, lookup, save, and retrieve information about the books I own or have read.
Acceptance Criteria:
 There is a web responsive design page where the user can enter the ISBN for a book.
 Validation of ISBN with error message (numeric, 13 digits long, starting with 9 and weighted sum
checksum)
 The ISBN is used to lookup book Title, Author, Number of pages using
https://developers.google.com/books/ API
 There is a way for the user to indicate they have or have not read the book
 A notes section allows the user to provide notes on the book
 All information is entered and presented on a single web page
 If the ISBN already exists in the database then return the stored information instead of looking it
up using the Google book API
 The web page makes asynchronous calls to a back-end server (that you create) to populate the
web page
 Use any language for the front end and MySQL for back-end service

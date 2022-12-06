Since I have done this project alone, I have tried to use as much data and tables i possibly could.

But due to less manpower i couldn't integrate all the tables and data values in the UI.

Although the library database created and the insert commands are valid and work proeperly as for the database table.


Dataset is in 3NF
I have used a total of 3 Main tables and created four more sub-tables, which are connected and dependent on the first 3.
Majority of the tables columns have a Varchar attribute since, most of the data is in text format except for the price, quantity,issue & return date which have int attribute.
Primary Keys :

a)publisher_PublisherName

b)book_BookID

c)library_branch_BranchID 

d)borrower_CardNo 

e)book_loans_LoansID 

f)book_copies_CopiesID 

e)book_authors_AuthorID 

Foreign Keys:

a)fk_publisher_name1 

b)fk_book_id1 

c)fk_branch_id1 

d)fk_cardno 

e)fk_book_id2 

f)fk_branch_id2 

g)fk_book_id3 



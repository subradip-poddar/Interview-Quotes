# Interview-Quotes
This is a data scrape of all the interview quotes of successfull professionals in a static webpage

Procedure: -

I used beautiful soup to extract the html code of the website.

Then in a function I extracted all the required details as mentioned.

I created a table to append quotes upto 5 pages and then created a DataFrame and coverted it to a .csv file.

Challenges: -

The quotes,date and the tags had the same HTML tag so I extracted the quotes using the parent tag of the entire body and for tags and date extract I created a seperate tag varibale having the extracted dates and tags and then used indexing to display them.


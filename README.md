# Reading List Tracker
I created a reading list tracker on Excel in order to identify the categories of books that I read the most and the amount of money I spent by using functions such as COUNTIF and SUMIF to create visual analyzations of my findings. I also wanted to keep track of the reading status of my books so I used the Data Validation tool to create a drop down menu. 

There are four different sheets that cover my findings:
* Bookshelf
* Owners 
* Categories 
* Status


### Bookshelf

I wanted to create a reading list tracker that I could personally use and update over time. This meant that I had to go through every book on my shelf and manually input them into the spreadsheet. 
This sheet has five columns that include data that I will use as a foundation. 
* Title
* Author
* Category
* Price
* Pages
* Series

![image](https://github.com/bmmontz/Bookshelf/blob/218e461d2bdaef7220415d9d084dc955eb33f640/Bookshelf.png?raw=true)

### Owners
The Owners sheet includes the same data as Bookshelf with an additional column, *Picked By*. This column has two different variables, each being the person who selected the book. I wanted to track who owns the most books on the bookshelf. 

I used the COUNTIF function to find the total amount of books that were picked by 'Bianca' and 'Jorge'.
I then createdd a pie chart to easily identify who has picked the most books.  

### Categories
 The Categories sheet used data from the Category and Pages columns to find which category is favored on the shelf with the SUMIF function. 
 
 ### Status
 This sheet includes a new column, *Status*. In this column I created a drop down list where I am able to select between *Read, Started,* and *Unread*. Since this is my personal bookshelf I wanted to be able to return to Tracker and adjust the status over time. 
 When looking at the data it is not easy to identify how many books are unread or have been started so I created a pie chart and a table using the SUMIF function. 

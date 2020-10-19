# pandas-challenge

Homework 4 - Heroes of Pymoli (Pandas)

	This Homework assignment was a real challenge. I am really struggling with pandas. The syntax of calling certain functions is confusing
and I feel like my approach to resolving exceptions was flawed. That said, I do feel significantly more comfortable working with dataframes
after completing the assignment. I understand the basics of forming them and pulling select pieces of data, but when I need to organize the data
in more complex ways I still need to practice.

	The biggest challenge for this assignment was understanding how groupby() objects work and which functions/attributes can be called
when working with them. After figuring how to use .count/.sum/.mean on groupby objects most of the problems I was having were resolved. 
I also struggled with formatting, but ultimately it was not as much of an issue as working using groupby. I just wish I had a better understanding of
what the individual pieces of this phrase: map("${:,.2f}".format), really do. I think I understand the '$' and the '2f' but the ":,." doesn't mean
very much to me right now, so that's one thing I would like to practice a bit more. I also ran into an issue with the last 2 pieces of the 
assignment (most popular items and most profitable items) where I had to create a duplicate df in order to get the correct values as the formatting
statement: map("${:,.2f}".format) was causing problems.

	It does feel good to have struggled with this assignment so much but to have finished with all my dataframes and summary tables looking
exactly the way that they should according to the file on gitlab. I definitely wonder where my code could've been more efficient but ultimately 
I feel pretty good about the work I am submitting. 

General Overview:
1. convert csv file containing purchase data for players in the imaginary game: Heroes of Pymoli, to dataframe
2. count the number of individual players
3. create summary table showing the number of unique items, the average price of all items, the total number of purchases, and the total revenue.
4. create summary table showing percentage & count of players organized by gender
5. create summary table showing purchasing analysis organized by gender
6. use bins to show the number of players organized by age
7. use bins to show purchasing analysis organized by age
8. use groupby to show who the top spending players are
9. use groupby to show  the most popular items in the game
10. use groupby to show the most profitable items in the game
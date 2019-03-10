# ExploringHackerNewsPosts

In this project, we'll work with a data set of submissions to popular technology site [Hacker News](https://news.ycombinator.com/).

Hacker news is a site started by the startup incubator [Y Combinator](https://www.ycombinator.com/), where user-submitted stories (known as 'posts') are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

You can find the data set [here](https://www.kaggle.com/hacker-news/hacker-news-posts), but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns: 
 - id - The unique identifier from Hacker News for the post
 - title - The title of the post
 - url - The URL that the posts links to, if it the post has a URL
 - num_points - The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
 - num_comments - The number of comments that were made on the post
 - author - The username of the person who submitted the post
 - created_at - The date and time at which the post was submitted

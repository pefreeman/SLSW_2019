
Can you predict how many comments a blog post will get in the next 24 hours?
---

This dataset contains information scraped from over 50,000 blog posts made
on Hungarian web sites in 2010 and 2011. Your job is to learn as association
(if it exists) between 27 different predictor variables and the number of
comments made on the post within 24 hours of a specified base time.

---

The data are contained in blogPost.Rdata:

predictors: 52,397 x 27

   comments.prebasetime: total number of comments before base time
   comments.prev24: number of comments in the 24 hours before base time
   comments.first24: number of comments in the first 24 hours after blog post publication
   source.avg.prebasetime: average total number of source comments before base time
   source.avg.prev24: average number of source comments in the 24 hours before base time
   source.avg.first24: average number of source comments in the first 24 hours after blog post publication
   links.prebasetime: total number of links/trackbacks before base time
   links.prev24: number of links/trackbacks in the 24 hours before base time
   links.first24: number of links/trackbacks in the first 24 hours after blog post publication
   length: length of the blog post (in characters)
   post.age: the length of time between the original blog post publication and the base time
   basetime.day: the day of the week of the base time
   post.day: the day of the week of the original blog post publication
   word1,..,word10: whether or not the word appears in the blog post (1 = Yes; 0 = No)
   n.parents: number of parent pages for the blog post
   parents.avg: the average number of comments the parent pages received
   parents.min: the minimum number of comments the parent pages received

response: 52,397 x 1
   -> number of comments made in the 24 hours after the base time


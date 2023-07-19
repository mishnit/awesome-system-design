## Functional requirements:

● Post: A user should be able to post some content with some optional media attached to it

● Search: A user should be able to search for another user or any post on the platform

● Home Timeline: The system should show relevant posts to a user when he lands on the home page

● Profile timeline: A user should be able to view another user’s profile and his recent posts

● Follow: A user should be able to follow others and see their no. of followers and following

● Like/Comment/Repost: Users should be able to like, comment, and repost an existing post

● Trend: Users should see the last 7 days’ top X posts based on no. of likes, comments, reposts

## Non Functional requirements:

● Low Latency

● High Availability

## Full Video Link:

https://www.youtube.com/watch?v=-HEsM_Dl--Q&list=PLmtNcpUq3YIJequI5FneNkiEGiHmwm3_o

![IMAGE](https://miro.medium.com/v2/resize:fit:1100/format:webp/1*ZxJ4gef99JZWz28e5e6nhw.png)

## Note:

Home timeline service acts as a post ranker and feed mixer. Ranking happens on the basis of number of likes, comments, reposts, media quality, tags and post creation timestamp while mixing happens on the basis of whether a follower wants to see all posts or only trending posts of a followee. We can maintain this preference in database mapped to follow service

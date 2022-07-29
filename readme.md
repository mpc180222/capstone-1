2 a) "Instant-Gram" (clone of Instagram) https://instant-gram-mpc.herokuapp.com/login or https://instant-gram-mpc.herokuapp.com/signup (test user is markdoe, password is password)
b) The website aims to clone functionality of the Instagram app.
c) I have implemented signup of new users, logging in and logging out, deleting user account, creating a new post (either a video or picture) with a caption for that post,
ability to view profiles of other users, to follow and unfollow other users, view the following and followed of any user, view their posts, 
like and unlike their posts, add comments to posts, like and unlike comments on posts, view who has liked a given comment on a post, delete owned posts,
as well as view a home 'feed' which consists of all posts by followed accounts from the last 7 days. This functionality is open to all registered users. If 
a user is anonymous (not logged in) they can view account profile pages and posts, but they are prohibted from posting or liking posts. There is also error handling
to prevent the user from seeing a database user if they try to manually access a post or account page that doesn't exist.

d) User logs in, or signs up, and is directed to their home feed, which is empty until they follow at least one account. They can follow some other users,
check out their posts, add comments, basically all of the activities described in c).

e) API was created by me.
f) Python, flask, SQL Alchemy, Bootstrap
g) The project was a lot of fun. I will continue to make improvements to it especially as I approach my job search.

# What is this?

This is a Node.js service that can be used to process contact and signup forms from a website.

# Why?

It is a lot cheaper to run a "static" website (e.g. on Amazon s3 or cloudfront) than it is a dynamic (e.g. PHP, JSP, ASP.NET, Express.js) one.  However, this is restrictive because it is common to have some way for a user to submit feedback, signup, or otherwise contact the website author.  This API allows for some JavaScript on the static site that sends the "signup" data to a backend hosted on a separate server.  

This may seem like it just moves the cost to another server, but in reality there are a lot of free and very cheap ways to host Node services, so the cost is smaller.
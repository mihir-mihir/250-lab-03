# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Mihir Singh

## Lab Question Answers

Question 1: 

One of the reasons RESTful APIs are scalable is that client-server interactions are
stateless, which means that the server doesn't have to remember any information
about past client requests. Another is that these APIs cache information in such
a way that some client-server interactions no longer need to be made.

Question 2:

The article defines "resources" as the information that the server gives the
client. The information that the mail server can provide to the client are:
* Details of a mail entry sent through a post request
* Whether or not an attempt to delete a mail entry was successful
* Details about an email with a given id
* All the mail entries sent to a given user
* All the mail entries sent by a given user

Question 3:

We didn't use any PUT requests, which update existing resources on the server.
We could add a dict of contacts that contains all emails of senders and
receivers as keys, and then use PUT requests to map those keys to names
associated with those emails.

Question 4:

RESTful APIs use API keys to block annonymous requests (each request must be
made through a specific API key), to control the number of calls made to the
API (by limiting calls/key, or the total number of keys available), and getting
information about ways different applications are using the API.
(https://cloud.google.com/endpoints/docs/openapi/when-why-api-key#:~:text=API%20keys%20provide%20project%20authorization,-To%20decide%20which&text=By%20identifying%20the%20calling%20project,or%20enabled%20in%20the%20API.)


# Student README

## Questions

1. The client and server have different sized buffers.  Why does it still work?
*the server  don't know the buffer size of the client.
2. What happens if the buffer size on the client is changed to a value smaller than the initial `message_length`?
*the massage is divided into letters.
3. What happens if you run the client when the server is not running? 
*connection error will happen.
4. What happens if you run the server while the server is already running?
*os error could happen.
5. What changes did you make to finish this assignment?
*i wiil change the server.py becuase running while loop from accepting connection added in for password to replace it to elif.
6. What resources did you use to complete this assignemnt?  Make a Markdown list of web links below.
*the youtube links in the atu.innomadic.com website.
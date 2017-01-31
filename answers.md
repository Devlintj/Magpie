#activity4
##Different Responses
###I want to build a robot. The response is "what would it mean to build a robot?"
###I want to understand French. The response is "what would it mean to understand French?"
###Do you like me? The response is "What makes you think that I like you?"
###You confuse me. The response is "What makes you think that I confuse you?"
###It handles "I want to" and "you/me" statements by returning a response that asks a question about the statement. It knows the statement by returning every character after the "I want to" or "you/me" statement.
##An example of when the "I something you" structure doesn't work.
###"I don't know you" gets the response "Why do you don't know me?". To solve this, you can check for words like "don't" in between both keywords and modify it to "not".

#activity2
##responses to statements:
###"My mother and I talked last night." asks about family
###"I said no!" asks why I'm negative.
###"The weather is nice." random non-committal response.
###"Do you know my brother?" asks why I'm negative.
##If statement sees if keyword is in my statement to respond to it.
##Three keywords and responses added.
###"kill" keyword gets the response, "killing is bad. Do I need to call the cops?"
###"Trump" keyword gets the response, "You know of the god emperor?"
###"car" keyword gets the response, "I hate those things."
##Question 1: What happens when a keyword appears in another word?
###It seems the bot will respond to a keyword even if it's only letters of a bigger word. The problem with this is that different words have different meaning, so if the chatbot can't tell no from know the chatbot will not be able to communicate well.
##not a question but it asked to explain how code deals with multiple keywords.
###The code responds to the first keyword triggered in the sequence of else if statements. IE if "no" is a keyword that get's checked before "mother", even if mother is the first word in the sentence, "Today, mother told me no", the "no" response will be triggered.

# Chatbot
Chatbot involves usage of Tensorflow, Nltk, NumPy and Tflearn libraries
that can be used to answer frequently asked questions for any commercial
purposes. The data used for training is custom made(JSON file) and can
be used according to one’s own needs.

The JSON file consists of a bunch of messages that the user is likely to
type in and mapping them to a group of appropriate responses. The tag on
each dictionary in the file indicates the group that each message belongs
too. Using this file, a neural network is trained to take a sentence of words
and classify it as one of the tags in our file. Thus finally, we can simply take
a response from those groups and display that to the user. More the tags,
responses, and patterns are provided to the chatbot, the better and more
complex it would be.

Problem Statement

Nowadays, people post a lot of stuff online, especially comments. Not all of it is good. Many times the language is abusive or toxic, which makes the platform worse for others.

It’s not really possible to check everything manually because there is just too much data. Even if someone tries, it takes time and still misses things. Basic systems that just check keywords also don’t work well because they don’t understand the meaning of the sentence.

So in this project, I tried to build a model that can automatically detect toxic comments. The idea was to make it understand the sentence instead of just checking words.

Objective

What I wanted to do in this project:

build a model that can detect different types of toxic comments
convert text into numbers so the model can process it
use an LSTM model to understand sequences
train it on a dataset
keep things consistent between training and testing
check how well it performs
Scope

This project only works with English text. It doesn’t handle images, audio, etc.

Also, since it depends on the dataset used for training, it may not always work well for new slang or tricky sentences.

Expected Outcome

At the end, I was able to:

train a model that detects toxic comments
classify text into multiple categories
create a working pipeline from input to output
give input text and get prediction scores
understand how NLP models actually work

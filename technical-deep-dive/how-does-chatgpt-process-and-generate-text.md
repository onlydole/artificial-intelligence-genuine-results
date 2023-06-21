# How does ChatGPT process and generate text?

Hello again! You've made it to the technical section of the course. We will dive into the nuts and bolts of how ChatGPT processes and generates text and how we can tweak it to suit our needs better. We'll keep it as jargon-free as possible.&#x20;

ChatGPT works by predicting what comes next in a piece of text. When you provide input, it considers the entire conversation history and generates a response, word by word, until it reaches a specified length or hits a stop signal like a full stop or a new line.

At its core, ChatGPT uses something called a transformer neural network. This network takes each word (or, more accurately, each token), looks at the context provided by all the other words in the text, and generates a representation. This representation is used to predict the next word in the sequence.

It's worth noting that when we say "word" here, we mean "token." In the language processing world, a token can be as short as one character or as long as one word. For example, "ChatGPT" would be split into three tokens: \["Chat", "G", "PT"].

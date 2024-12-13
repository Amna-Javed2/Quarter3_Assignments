# Assignment 01: Understanding OpenAI Chat Completion API Parameters

## 1-Messages:
Messages are the way of communication between the user and the AI.

Example:

{"role": "user", "content": "Hello, how are you?"}

{"role": "assistant", "content": "I'm fine, thank you! How can I assist you today?"}


## 2-Model:
This parameter specifies which version of the AI model is being used to generate responses.


## 3-Max Completion Tokens:
This parameter sets the maximum number of tokens(words) that the AI can generate.It controls the length of the output.


## 4-n:
This parameter determines how many variations of the response the AI should generate.

For example, if n is set to 3, the AI will produce three different responses to the same input.


## 5-Stream:
It allows the AI to send parts of the response as they are generated, instead of waiting for the entire response to be finished.


## 6-Temperature:
This parameter controls the randomness of the AI's responses. A higher temperature makes the output more creative, while a lower temperature makes it more specific and focused.


## 7-Top_p:
This parameter decides which top responses the AI should consider.If you set top_p to 0.9, the AI will only look at the top 90% of the most likely responses.


## 8-Tools:
This parameter allows the AI to use additional tools or plugins to enhance its capabilities. For example, it might include tools for web search, code generation, or image creation.

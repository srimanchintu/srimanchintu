import openai

openai.api_key = api_key

response = openai.ChatCompletion.create(
    model="gpt-3.5-turbo",
    messages=[{"role": "user", "content": "Hello, ChatGPT!"}]
)

print(response['choices'][0]['message']['content'])

 ## i have done it api integration by using python

#OUTPUT
[Hello! How can I assist you today ? ]

# Ai-Detection
Uses chat-gpt to detect if an essay or anything written is written by Ai. 

Make sure to replace 'YOUR_API_KEY' with your actual OpenAI API key. This code uses the text-davinci-003 engine for text classification, but you can explore other models or adjust the parameters according to your needs.

Note that this approach relies on the OpenAI API and may incur usage costs. Additionally, it is important to keep in mind that AI detection is a challenging problem, and there might be instances where AI-generated text can still go undetected or incorrectly classified. 

the API key is retrieved from the OPENAI_API_KEY environment variable using os.environ.get('OPENAI_API_KEY'). Make sure to set the environment variable with your actual API key before running the code. By using environment variables, you can keep your API key hidden and separate it from the code itself, adding an extra layer of security. 

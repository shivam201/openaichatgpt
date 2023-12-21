# openaichatgpt
Chatgpt
1. Create account using this link - https://beta.openai.com/signup/
2. left hand side open APIKeys 
  - Generate Key - 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
3. Find the path of pip inside Python\Scripts\ folder and create new path.
4. Open Python and run this 
  - pip install openai
5. Copy Code

# Import the OpenAI library.
import openai

# Set the OpenAI API key.
openai.api_key = '**********'

# Create a completion request.
response = openai.Completion.create(
    # Specify the engine (e.g., davinci-codex)
    engine="davinci-002",

    # The prompt to complete.
    prompt="Tell me a joke.",

    # Set the maximum length of the response.
    max_tokens=30,
)

# Print the first choice.
print(response.choices[0].text.strip())

6. Execution Python File and you will get output.
   

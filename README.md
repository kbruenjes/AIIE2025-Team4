# AI Children's Book

The Team:
- Jaiden 
- Keegan
- Kevin

# The Idea

Our AI project will create a short, nine to twelve page children's picture book based on a provided input. The general process of how it will work is as follows:

# The Prompt

The prompt will consist of 2 components:
- The story prompt (Ex. "A frog goes to water park for a day")
- int pages (This value should be between 5 and 8, and not equal to the total amount of pages)

Story Prompt is fed into 2 functions:
- GenBeginning()
- - Creates a concatenated string of "Create the first two sentences of a short children's story with the prompt: insert_prompt"
- - Returns the response

- GenEnd()
- - Creates a concatenated string of "Create the last two sentences of a short children's story with the prompt: insert_prompt"
- - Returns the response

Afterwards, the two responses could be fed into another function:
- GenMiddle()
- - Given the beginning sentences and the end sentences, have the AI generate the x amount of pages in the middle, where x is pages from the prompt components

Alternatively, just tell the AI to write a story based on the prompt with x amount of sentences and hope that works

# The Images

The AI will then generate a cartoon image for each sentence of the story
- Call the image generation once for each sentence in the list of sentences

Once all of the images are completed, have the program print each image with the sentence underneath it
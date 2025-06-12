# AI Children's Book

The Team:
- Jaiden 
- Keegan
- Kevin

# The Idea

Our AI project will create a short, nine to twelve page children's picture book based on a provided input. The general process of how it will work is as follows:

# The Prompt

Story Prompt is fed into GenText()
- Generates a story based on the provided text prompt. Also requires an input for a story for the model to base the prompt off of

# The Images

The story is fed into GenImage()
- Called once for each sentence in the list of sentences
- Also takes input for reference images to be used for styling, can take multiple images at once
- Takes a self generated note on the previous panels to help with continuity errors

# Printing

After everything is generated, print_story() function is called to display all of the images with their captions underneath.
# Madlibs 
## Overview 
Madlibs is a word game where players fill in the blanks of a story with random words or phrases, typically without knowing the context. The result is often a humorous and unexpected narrative.

## Requirements 
To create a Madlibs game using Python, you'll need:

- Python installed on your system (https://www.python.org/)
- A text editor or an integrated development environment (IDE)

## How to make one 

1. Choose a Story: Start with a simple story or create your own, leaving blank spaces for nouns, verbs, adjectives, etc.

2. Create a Template: Convert your story into a template by replacing the blanks with placeholders, such as {noun}, {verb}, or {adjective}.

3. Get Input from Users: Use Python's input() function to collect words from users for each placeholder. Store these inputs in variables.

4. Fill in the Blanks: Substitute the placeholders in your template with the collected words.

5. Display the Result: Print the completed story for users to enjoy the humorous and often nonsensical outcome.

### A simple Code snippet as example

```python

# Choose a Story
story_template = "Once upon a time, there was a {adjective} {noun} who loved to {verb}."

# Get Input from Users
adjective = input("Enter an adjective: ")
noun = input("Enter a noun: ")
verb = input("Enter a verb: ")

# Fill in the Blanks
completed_story = story_template.format(adjective=adjective, noun=noun, verb=verb)

# Display the Result
print(completed_story)

```

> [!Tip]
> Make sure you have a longer storyline to get more awesome funkier stiries. Also make sure you expand this project further more... 

# Story Teller

There are 5 agents that set the ground for a story:
- Place Agent - it determines the place where the story will be set
- Time Agent - it determines the time the story will be set
- Characters Agent - it creates a list of 1-3 characters that will be featured in the story
- Items Agent - it creates a list of 1-3 items (objects, animals, plants, etc.) that will appear in the story
- Mood Agent - it sets the mood for the story (sad, whimsical, melancholic, etc.)

Then there are tools:
- a tool that sends an email to a specified recipient
- the five agents listed above used as tools

Then there's a story manager that uses the elements generated above to create a story and send it via email.

There's also a handoff - another agent turns the story into HTML and sends it via email.

Here's an example of an email with a story that the recipient could expect:

<img width="1580" height="699" alt="image" src="https://github.com/user-attachments/assets/eb3aad71-4752-48a7-a25e-7afe926cec2d" />

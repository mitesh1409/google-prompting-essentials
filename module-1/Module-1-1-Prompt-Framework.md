# Get the most out of AI with the prompt framework

Getting the most out of generative AI is all about understanding inputs and outputs. What are you hoping to get from the tool? That’s the output. What kind of prompt is going to help you get it? That’s the input. And there’s a simple framework that helps you provide clear and specific directions to any gen AI tool: Thoughtfully Create Really Excellent Inputs, or Task, Context, References, Evaluate, and Iterate. This prompting framework will come up throughout this course, so you might want to say it out loud or write it on a sticky note for your desk. Here are the components:  

![Prompt Framework](./TCREI.png)

---

## Specify the task

Crafting a great prompt starts by describing the task you want the tool to help you with. The task is the foundation of any prompt. It’s what you’re asking the gen AI tool to do for you. Adding a task to your prompt is like writing a sentence asking someone to do something for you: 

Write a list.

Draft a speech.

Create an image.

These are all tasks that a gen AI tool can help with.

When you’re writing a task, you need to be clear and specific about what you want. If you write a task with vague instructions, it can result in an output that’s irrelevant or incorrect. 

To avoid that, give your tasks some specific details. That includes providing a persona and a format:

- Think of a persona as the expertise you want the gen AI tool to draw from. You can ask the tool to take on the perspective of a science expert or an industry analyst, or ask it to create an output geared towards a specific audience, like your manager or team.

- The format is what you want the output to look like. Want a bulleted list? Or maybe a table so you can compare results side-by-side? Include those details in your task.

Here’s an example of a prompt that includes task, persona, and format: 

You’re a movie critic that specializes in Italian film. Create a table that contains the greatest Italian films of the 1970s, and separate them into genres like thrillers, dramas, and comedies. Provide a 100-word summary of each movie as well as details about the production including director and release year.

---

## Include necessary context 

When it comes to prompting, oversharing can be good. The more relevant details you include, the better your output will be. Providing lots of background information—like your goals, the reason for the task, or what you’ve tried before—rounds out the model's understanding of what you're looking for. These details are called context, and they’re a vital part of creating great prompts.

For example, you could write: 

How was DNA discovered?

Instead, write a prompt that includes detailed context or background information:  

You’re a science expert developing a new curriculum at a local college. Tell me in a couple of engaging paragraphs how DNA was discovered and what kind of impact it had on the world. Write it in a way that people unfamiliar with science would understand. You have gotten feedback from students that they found this course dry and unintelligible before, so you want to make sure that the explanation grabs the students' attention and makes a good first impression.

Context has the potential to be the longest piece of a prompt. As you add more of it to your prompts, you may want to consider using delimiters, which not only act as extra pieces of context, but help differentiate parts of your inputs. Delimiters are special symbols that keep prompts tidy and increase the likelihood of generating a useful output. Think of them like labels or guard rails that tell the tool, "This is the task," "This is the context," and so on.

Some popular delimiters include:

- Triple quotes ("""): These create a distinction between the different elements of the prompt, like your task and context. They’re useful for when you want to clearly separate text within a prompt to signify different meanings, purposes, or other distinguishers.  For example:

Write a social media post based on the following announcement:

"""  
Our annual company picnic will be held on Saturday, June 24th at Bicentennial Park. We'll have food trucks, lawn games, and live music from 11am to 4pm. All employees and their families are welcome to attend.  
"""  

- XML tags: These are like labels that mark different sections of more complex prompts. For example, add “<task>” to make it super clear where your task begins and “</task>" to indicate where it ends.

- Markdown tags: These are symbols you can use in prompts to add formatting. For example, if you were to use a gen AI tool to copy-edit your work, you could surround text with “_” to italicize it or “**” to bold it. This preserves your formatting as you move it into a gen AI tool, which generally uses plain, or unformatted text. 

---

## Provide references 

References are examples or any additional resources that resemble what you want the gen AI tool to produce. Including references in a prompt is like showing your hairstylist an image of someone with the new haircut you’d like to try.

Depending on the gen AI tool you’re using, you can include text, images, and even audio references to sharpen your input. Whether you share your own work or include external references, clearly identify how they fit into your overall objective so the gen AI tool understands exactly what to emulate. And no need to build an exhaustive set of references—two to five should be enough.

For example, you could write: 

Write a product description for a watch like it’s in a magazine.

Instead, write a prompt that provides relevant details, references two external resources, and identifies a format: 

Write a one-paragraph product description for a high-end watch with features like a scratch-resistant case and a water resistance rating of up to 30 meters. Base the description style on these examples from our website:

- Sunglasses: Our latest collection of handcrafted, heritage-inspired sunglasses features details like UV-protective lenses in shades specifically chosen to complement each frame—all at a price that won't break the bank. Plus, we made these sunglasses with vintage-inspired acetate frames and a keyhole bridge.

- Cardholder: Crafted in smooth Italian leather, this double-sided cardholder is designed to carry your cash and credit cards without the bulk of a full wallet. Fun fact: this cardholder is made in Naples, Italy, and will look great when you treat your friends to a round of summer spritzes.

---

## Evaluate your output 

Different AI models are trained on unique data and rely on different programming techniques. Some models may be better suited to specific uses like writing code or brainstorming ideas, while others might have limited outputs because of their training sets. No matter the model, running the same prompt multiple times will likely render different results because of how gen AI tools process data. 

That’s why it’s so important to evaluate your output. Before you use any AI-generated information, text, or materials, critically evaluate that the output is accurate, unbiased, relevant, and consistent before incorporating it into your workflows. If the output isn’t what you’re looking for, you should iterate on your prompt. 

---

## Take an iterative approach 

There will be times when your prompt simply isn’t leading to the output you need. That’s where our ABI advice comes in: Always Be Iterating. If you find an output lacking, continue clarifying what you need until it’s just right.

The prompting framework sets you up to give gen AI tools the information they need to generate useful outputs—and it’s designed to apply across all kinds of tools and models. So whatever your gen AI tool of choice, make sure you specify your task, provide context and references, evaluate your outputs, and iterate your inputs. 

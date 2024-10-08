# pattern-prompts
collection of the Prompts
an AI researcher posted this prompt. it lets Sonnet perform equal to OpenAI o1 Level 2 AI. Here is the prompt in sonet-equal-to-o1-level2 file.
I have been told this is from an x/twitter.  I need to find the original author to credit him.

## How to use the prompt
1) go to your favorite AI language model (for example, https://claude.ai and pick 3.5 sonnet)
1) paste that long prompt in this file of this repository: sonnet-equal-to-o1-level2 
1) Following that, enter your prompt, such as, "Write a recipe for chocolate chip cookies with walnuts" (or whatever)
1) press Enter
1) look out the window for a while
1) Your AI has written a detailed recipe for you.

## How tags to be used in a prompt
For people less familiar to HTML or XML markup language, here is the explanation:
~~~
<thinking>
Ah, I need to explain the angle brackets (<>) used in markup languages, focusing on proper terminology while keeping it accessible. This is a fundamental concept in markup languages like HTML and XML.
</thinking>

<answer>
# Understanding Angle Brackets in Markup Languages

The symbols `<` and `>` are called "angle brackets" or "chevrons" in markup languages. They are used to delimit (mark the boundaries of) tags.

Basic Syntax:
- Opening angle bracket: `<` 
- Closing angle bracket: `>`
- Forward slash for closing tags: `/`

Structure of a tag:
```
<tagname>content</tagname>

Where:
- < > are angle brackets (chevrons)
- tagname is the element name
- </tagname> is called the closing tag (note the forward slash)
```

Think of angle brackets like parentheses in mathematics - they group things together and tell you "this is a special instruction." In markup languages, anything between `<` and `>` is treated as a tag rather than regular content.

Technical terminology:
- The combination `<tagname>` is called an "opening tag" or "start tag"
- The combination `</tagname>` is called a "closing tag" or "end tag"
- Together, they form an "element"
- The text between tags is called the "content" or "element content"

</answer>

<reflection>
This explanation provides the correct technical terminology for angle brackets while using a mathematical analogy to make it more understandable for newcomers.
</reflection>
<reward>0.9</reward>
~~~

By now, you can catch the patterns, and the contents between the "tags" have special meaning in the context of the tag name, which should be self-explanatory.
~~~
<thinking>
Ah, I overcomplicated the request. Let me create a simple, shareable list of markdown tags with brief descriptions - perfect for a GitHub readme or quick reference.
</thinking>
<answer>
# Available Prompt Tags

<thinking>...</thinking> - Contains internal reasoning and analysis process
<step>...</step> - Defines individual action items in the solution process
<count>n</count> - Shows remaining steps from initial budget (starts at 20 by default)
<reflection>...</reflection> - Evaluates progress and effectiveness of current approach
<reward>0.0-1.0</reward> - Scores solution quality (0.8+ continue, 0.5-0.7 adjust, <0.5 revise)
<answer>...</answer> - Presents final synthesized solution or response

Note: Tags can be nested and used in combination to structure complex problem-solving approaches.
</answer>
<reflection>
This version is much more concise and suitable for sharing - exactly what was needed for a GitHub post.
</reflection>
<reward>0.9</reward>
~~~

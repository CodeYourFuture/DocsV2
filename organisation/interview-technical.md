---
id: interview-technical
title: Technical Interview Guide
---

## The Aim

The aim of a tech part of the interview is to determine if:

1. the student understands the HTML and CSS basics they've presumably learned and used to a sufficient level to allow them to manipulate their page further or to recreate it from scratch (if they were asked to).
2. the student has picked up any process for searching for and incorporating new information
3. the student can reason through some small problems
4. the student can express technical questions or explanations fairly clearly in english
5. the student can read a simple task statement in english (not assessed here, yet, sadly)

The conversation arising from the questions will also expose student's levels of comprehension and articulation in the English language, and their some of their thought process.

These questions avoid the possibility of them reciting prepared, scripted answers with no/limited understanding.

## Questions

### Can you give me specific questions?

Specific questions are hard to suggest as each student will have created something different.

A few are suggested below, for the "product landing page" task.

### What sort of questions should I ask, then?

Ask questions which would require:

- change of element types
- change of element attributes
- duplication and alteration of elements
- css alterations
- re-ordering of elements
- removal of elements
- for them to google something related and relatively easy which they don't know (e.g. a css rule or html attribute) such that they could potentially find the answer and make use of it in a (say) 1-minute window.

### Guidance on creating and asking questions

- DON'T get bogged down in minutia
- It's fine to ask questions that the student might not know the answer to or which might be considered advanced. Just be positive and make it clear that they're not expected to know the answer!

### A few sample questions for the product landing page task

How would you change your code if...

1. We want NO video when viewing with a small-screen mobile device (e.g. smartphone)
2. We want clickable links from your landing page to your tribute page and vice versa, maybe at the foot of the page.
3. The company has a partner that wants their logo added to the header, too! https://placekitten.com/200/100
4. We want the navbar to always be shown at the **bottom** of the viewport, instead of the top?
5. \[Ask this AFTER "playing ignorant", below\]. What if I wanted to collect email address AND full name?
   (Note copy paste isn't quite enough here - they'd have to disable validation of the name field as an email address)
6. We want to add a sound file to the page (or a playable video game, if they already know) \[Here we're intentionally asking for something they've hopefully no clue how to do. DON'T have them waste time taking this all the way, even if they can. You just want to at least see that they can search and start to select from search results intelligently.\]

### Playing Ignorant

Make a "mistake" understanding the email address form field, and see if they can help you.

- You: "This form field of the form rejects when i try to submit my name ("Neill"). What's going on?"
- Hint (if necessary) so they don't treat you as infallible: You: "Am I doing something wrong? I might have the wrong idea here..." ... "I might be _intentionally_ making a mistake here, what mistake am i making?"
- what we're looking for:
  - candidate understands our mistake - it should be enough for them to read the presented error message
  - can articulate to us why we're seeing an error and what we might do to remedy it
  - can explain how this validation has been enabled in their html code.
- Follow up: You: "Ah! So how do you get it to validate an email field?"

### Break and fix

Fork their site and break it (e.g. cause elements to become unstyled by changing element ids or classes). Point out the errors from the user perspective (not from a code view), and ask them to fix your code.

Make sure you're agreed on what the client expects: "We want this footer text to be neon pink, and ten feet tall, right?"

How do they go about debugging it?

Here are some likely hints (if they struggle for a while):

- \[First check you have the same expectation\]: "We expect this text at the bottom of the page to be bright pink, right?"
- "How would you do that in the first place? Forget that I _broke_ it - do it from scratch as you would for any text." \[avoid them obsessing on what got broken, or how. guide back to first principles.\]
- "How does it know that this rule in css is meant for _this_ text?" \[Looking for the aha of a wrong class or id\]

## Rubric (TODO)

For each question:

### Understanding the question (forget about the answer for now)

- Clearly understood the question
- maybe understood the question
- probably didn't understand the question
- I had no chance to assess this

### Approach

- showed an excellent approach to the question
- showed partial signs of a good approach to the question
- showed a poor approach (e.g. helplessness)
- I had no chance to assess this

### Knowledge

- Knew the answer
- Was clearly familiar with the domain and got to the answer after light hint(s)
- Didn't know the answer
- I had no chance to assess this

### Taking feedback

- neutral - no opportunity for feedback arose
- clearly took feedback well (acknowledged and/or incorporated or rejected with reasoning)
- took feedback poorly (denial / no acknowledgement)
- I had no chance to assess this

### English language

- communicated fluently in english
- communicated passably in English, had one or two problems but we definitely understood each other
- communicated poorly in English - I repeatedly had troubles understanding what was being asked or articulated, even after asking for clarification.
- I had no chance to assess this

### Other notes

- any other notes on the question?

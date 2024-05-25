# Assignment 2

Your Assignment 2 work should be done in the general assignment repo you accepted last week. If you haven't yet accepted it, you can [do so here](https://classroom.github.com/a/aS7pjGjo).

## Details

**Team Member Website 2.0**

For the second assignment, you’ll be essentially re-creating your assignment 1, but this time with React & Redux! The requirements are slightly different, and you may use as much of your assignment 1 code as you would like, or create something new if you’re feeling adventurous.

We’re expecting the following:


1. You MUST use React & Redux, and start your assignment with the Vite boilerplate code (see Workshop 2 slides). Remember, you will be asked to explain sections of your code.

1. A form with multiple inputs, to take in a member name, description, age (or other numerical category), and image, as well as a button to add the member to a list, and a button to clear the inputs in the form.

1. Some pre-loaded member list data to initialize your reducer.

1. Display a list of members that contains the member name and image (the list should be updated with a new item whenever you click the add button).

1. *NEW* INDIVIDUAL/DETAILED ITEM VIEW - The ability to select a member to view in a dialog or popup.The goal here is for this “detail” view to know which member was selected, and show the description and age for that item. The detailed view MUST be its own React component.

1. Basic styling. (Do not spend too much time on this, and re-use as much as you’d like from Assignment 1! You will not be graded on Unit 1 material.)

1. Something cool and extra! This is wide open for you to explore, and try to push your knowledge and boundaries. Must use Unit 2 technology (React & Redux) to complete this requirement. 

### Basic Examples

- you could have individual buttons for each member that will allow you to delete them (a button with an X or that says delete)
- you could have additional form elements that add additional data for each member

```{warning}
**Note for Implementation:** DO NOT try to take your assignment 1 code, and re-shape it into React components. Instead, start with the Vite boilerplate, and think about how you would organize your component structure. Begin to create those components, and then copy over pieces of your assignment 1 code as needed. Remember that rendering the view is handled much differently in React. If you find yourself needing to use HTML DOM functions (e.g. `document.getElementById`, or `appendChild`), then STOP, and try to think of the "React" way to do the same thing.
```

As described in the individual assignment rubric, your code will need to meet these requirements and be functional, up to perhaps a few minor glitches in tricky cases. Note that functionality includes both user-visible and console-visible issues.

It’s up to you! We’re hoping that you’ll use the above requirements as a guide, but that you’ll let your imagination take over, and build something unique and interesting!

You should be ready to demo this to a TA during your second week lab, and should be ready to answer questions about it, as well as explain what you’ve done.

HAVE FUN!!!

## Grading Rubric

You can see the [grading rubric here](page_rubric):

## Submission Instructions

- Your final code must be committed to an `Assignment2` branch in a Github repo before the due date.
- You will need to submit a link to your branch on Canvas before the due date.

## Frequently Asked Questions

- **Can I use MaterialUI, Sass, other styling tools?** Yes, it will not count towards your assignment grade, so do not put too much effort into styling. Do NOT use pre-built React components. (That goes beyond styling.)

- **Can I use pre-built React components such as a datePicker or React Dialog or Modal?**
No - do not import any React components. You need to write all your components from scratch for the assignment. You are allowed to import pre-built React components for your project.

- **For my “extra feature”, can I add some cool animations?**
Sorry, no - The “extra feature” MUST display your technical abilities in React & Redux, so features involving styling won’t count.

- **Can I follow a React or Redux Tutorial?**
Yes! Please do. If you are using code from the tutorial, you MUST write a comment with a link to the tutorial. You also must be able to explain all and any parts of the code.


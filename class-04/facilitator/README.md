# Facilitators Guide: Responsive Web Design and Regular Expressions

## Overview

Today's class is a combination of more CSS topics and an introduction to regular expressions. This is the first of two days where regular expressions will be covered, so keep the demo to the basics and show multiple examples. There is an additional pattern matching lecture later in the course, with corresponding code challenges.

There are several tools students should bookmark for reference when practicing pattern matching with regular expressions; they are listed in the readings for today's class. Use these tools when introducing the topic.

## Learning Objectives

Review the detailed objectives in today's [student-facing readme](../README.md).

## Preparation

- Prepare a demo on regular expressions. This can be delivered using an online RegEx tool.
- Prepare a demo on CSS grids and icon fonts from IcoMoon or Font Awesome.
  - Complete the [CSS Grid Garden](https://cssgridgarden.com/) training.
  - Review and practice techniques at [CSS Tricks Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- Review the starter code for the portfolio assignment. Students can fire this up in the browser using `live-server` or you can point them to the source at [HTML5 UP](https://html5up.net/prologue).

## Lecture Outline

Below is the expected lecture outline and flow. One possible way to present this material is documented in the [example lecture](../facilitator/LECTURE-EXAMPLE.md) notes.

### Warm-Up

- **Student Analysis** (5 min)
  - Show or print the [warm-up code](../warm-up/warm-up.md)
- **Debrief** (5-10 min)
  - Refer to the [Warmup Notes](../warm-up/NOTES.md)
  - Optionally demo the running code at Repl.it

### Shred Talk

- **Why**
  - Daily "Shred Talks" introduce the student to a new javascript coding concept, setting them up to complete the daily "Code Challenge" series
- **What**
  - Refer to the [challenge documentation](../challenges/README.md)
- **How** (10 min)
  - Follow the [Demo Code](../challenges/DEMO.md)
- **Note**
  - If you are short on time, this can be omitted from class lecture. There are official videos that students can watch in lieu of you leading this portion of class.

### Code Review

### CSS Grid

- **Why** (5 min)
  - Grid is the next generation of web page layout
  - Mimics a table structure, making it far easier to apply complex layouts
- **What** (10 min)
  - Grid uses a 2-D row and column layout system
  - Very reminiscent of using `<table />` to design sites years ago.
- **How** (30 min)
  - There's a short [Grid Demo](../demo/grid/) that shows how columns work.
  - Demonstrate the "Holy Grail" layout, progressing it from Float to Flex, to Grid.
    - Compare and contrast as you go.
- **Experimentation and Discovery Ideas**

### Regular Expressions

- **Why** (5 min)
  - Match Patterns in strings
    - "Find Stuff"
    - "Easy to remember" once you get over the hurdle
    - Every language supports these.
- **What** (10 min)
  - Matching rules within delimiters, followed by a modifier
  - `/abcdefg/ig`
    - `/` and `/` are the delimiters. The thing to match goes between them.
    - `ig` at the end are modifiers, meaning "Case Insensitive" and "Globally (don't stop when you find the first one)
    - The pattern to match (goes inside the delimiters)
      - Can contain raw characters, group indicators, and several special characters to change how the regex matches.
- **How** (30 min)
  - <http://www.regex101.com>
  - Demonstrate:
    - Basic string, number, special char matching
    - Groups
    - Starts/Ends with
    - Counting things (3 numbers)
- **Experimentation and Discovery Ideas**
  - If time allows, demonstration how to create a fuzzy search in the photo gallery solution code to search for images by matching keywords.

## Lab Notes

- This will be a solo lab - building out the first part of the portfolio
- The starter code is a template with a 5,000+ line .css file
- Students will need to modify the content and apply SMACSS rules to the css

## What changed from the previous class?

- This is a completely new topic

## What might students struggle with today?

- The size of the .css file will seem daunting
- Regex are very confusing at first
  - Today's code challenges are tough as a result.

## Past bugs, issues or surprises...

## General Comments and Notes

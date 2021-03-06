# Week 01

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## HTML

### Question #1

What does it mean for an HTML tag to be "semantic"? Give an example of a short snippet of HTML written using semantic tags and non-semantic tags.

```text
semantic is for text-only.

<h1>This is an example of a semantic tag</h1>

<h1><b>While this included format </b> too.</h1>


```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The alt attribute, or alternative text, is primarily intended for ADA compliance for screen readers for the blind. It can also indicate the presents of an image and a description of an image file if the image hasn't/can't load.
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
Defines information that's used in the document but is not necessarily "seen" in the document like html. For example, a link to the css styles for the page or a title of the page when opening in a web browser.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
outline: Defines the distance between an element's border and adjacent elements' borders.
margin: Inserts a "wall" around an element.
padding: Defines the distance between an element's content and its border.
___: Defines the width of an element.
border: Overlays a "wall" on top of an element.
___: Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
*** note for self: look up/try, unsure on what this is asking and answer***

[] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[X] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1. css style sheet
2. <head> section of an html page
3. within the html itself, e.g. bolding words using <b>
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A fork creates a branch, a copy of code, that you can work on without fear of damaging the master. The updated code can later be merged with the master to improve the master. A clone is more general, copying information without a way/intent to push updates to the master branch later.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git fetch will pull information from any source of code (or multiple), more broad than git pull. Git pull is a type of fetch, it's specific to pulling from a branch/rework and integrating into another branch or master.
```

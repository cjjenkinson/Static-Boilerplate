[![Front‑End_Checklist followed](https://img.shields.io/badge/Front‑End_Checklist-followed-brightgreen.svg)](https://github.com/thedaviddias/Front-End-Checklist/)

# Pre Front-end Boilerplate

A very lightweight front-end boilerplate for kicking off a project, no pre-processors or workflow automation tools just single page template and style structure utulising CSS variables for maximum flexibility and speed, hence the name pre.

Whenever starting a new project I often need to get a single index page and style structure in place. This is the boilerplate that I always arrive at whenever starting from scratch.

#### File structure:

```
+-- css
|   +-- app-name.css
|   +-- base.css
|	+-- normalize.css
|	+-- variables.css
+-- .gitignore
+-- index.html
```

#### CSS:

`app-name.css`

Update app-name.css to the name of the project, then reflect the change on the index.html stylesheet link.

Imports all CSS files which is linked to from index.html

`base.css`

Contains base styles and resets such as body, typography etc

`normalize.css`

Makes browsers render all elements more consistently and in line with modern standard

`variables.css`

Uses the root decleration to hold all of the CSS variables used throughout your stylesheets

**CSS variables** are entities defined by CSS authors which contain specific values to be reused throughout a document. They are set using custom property notation (e.g. **--main-color: black;**) and are accessed using the [`var()`](https://developer.mozilla.org/en-US/docs/Web/CSS/var()) function (e.g., `color: **var(--main-color)**;`) .

Read more about using CSS variables: [Using CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)

--

Guided by the http://frontendchecklist.com/ - I would strongly advise using the Frontend Checklist for further best practice, testing and accesibility checks as you progress forward.
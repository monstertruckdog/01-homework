# About "Horiseon" Index Page

## Background

The first graded homework assignment ("*) asks students to "refactor" given HTML and CSS code files for a company homepage, "Horisean".  From the assignment [README](../README.md):

> ...your homework is an on-the-job ticket&mdash;meaning that you'll begin with starter code that you need to modify.
> ...
> check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

### Requirements

The [README](../README.md) also provides the following requirements, or "Acceptence Criteria," for the assignment:

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

### Expected Outcome

An image of how the web page should appear was provided to the student to use in writing their refactor code.  The final outcome of the refactor code should result in minimal or no visual difference between the provided image of the web page and the image of the refactored web page.

#### Desired End Product

<img src="./assets/images/01-html-css-git-homework-demo.png" width=25% height=25%>

----

## Edits

Code changes made to the forms can be observed from the GitHub UI, but notes on these edits have been listed here for more details.


### HTML:  `index.html`

#### Sumamry of changes

* Wrote a more descriptive <title> for the page
* Create a `<meta>` tag with a `description` attribute to increase site accessibility and hypothetical visibility in search engine search results
  - [I used a SERP tool](https://blog.spotibo.com/serp-preview-tool/) to preview how this tag would look in a search from a google.com search
* Modified `<div>` elements by changing tag to more specifc semantic element name
  - `<header>`
  - `<section>`
  - `<nav>`
  - `<aside>`
  - `<footer>`
* Modified values for `class` for `benefit-...` items and for former classes `search-engine-optimization`, `online-reputation-management` and `social-media-marketing` to increase code readibility, and to reduce redundancies of CSS sytling
* Verifed internal page section hyperlinks are linked correctly to the appropriate element `id` and function correctly


### CSS:  `style.css`

#### Summary of changes

* Reduced total number of lines from 200 to 132
* Updated page element names "`aside`," "`section`," and "`footer`" to correspond with respective HTML element updates
* Grouped element types together:  page elements, then classes (no IDs were used)
* Condensed former `benefit-...` class styles into one style block (`benefit-item`) to accomodate class name change in HTML and to reduce repetition of style code across different content items
* Condensed former classes `search-engine-optimization`, `online-reputation-management` and `social-media-marketing` into one style block (`services`) to accomodate class name change in HTML and to reduce repetition of style code across different content items

----

## Submission

Final work on assignment can be found at the following locations:

* **GitHub**:  [`homework1` Repository](https://github.com/monstertruckdog/homework1)
* **GitHub > GitPages**:  [Hosted assignment submission](https://github.com/monstertruckdog/homework1/Develop/index.html)

# About "Horiseon" Index Page

## ! TO DO !
  
* Add `alt` attributes to images!
* Make `nav` links more "accessible" through display styling
* Condense "HTML" to bullet points
* Display image of mockup somewhere
* Refactor assignment file directory as it appears on Git
  - Pull `index.html`, `style.css` and other assets out of nested folders so `index.html` can sit at `root`

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

## Edits

Code changes made to the forms can be observed from the GitHub UI, but notes on these edits have been listed here for more details.


### HTML:  `index.html`

| LINE # | DESCRIPTION OF CHANGE(S) |
| --- | --- |
| 7 | Wrote a better title label for the page |
| 8 | Created `description` meta tag for better site accessibility; [used a SERP tool](https://blog.spotibo.com/serp-preview-tool/) to preview how it would look in a search from google.com |
| 12 | Added starting `<header>` tag to improve semantics tags |
| 14 | Modified tag to `<section>` to improve semantics |
| 15 | Modified tag to `<nav>` to improve semantics and increase accessibility with 'aria-labelledby` attribute |
| 16 | Updated class name to correspeond with `<nav>` attribute |
| 27 | Added closing `</nav>` tag |
| 28 | Added closing `</section>` tag |
| 29 | Added closing `</header>` tag |
| 30 | Added comment to describe purpose of `<div>` element since it has no content |
| 31 | Modified tag to `section` to improve semantics |
| 32 | Modified `class` name to minimize CSS code resuse between similar content; left the `id` attribute so that internal page section links would still work |
| 39 | Modified `class` name to minimize CSS code resuse between similar content; left the `id` attribute so that internal page section links would still work |
| 46 | Modified `class` name to minimize CSS code resuse between similar content; left the `id` attribute so that internal page section links would still work |
| 53 | Updated closing `</section> ` tag |
| 54 | Modified tag to `<aside>` to improve semantics
| 55 | Modified `class` name to minimize CSS code resuse between similar content |
| 62 | Modified `class` name to minimize CSS code resuse between similar content |
| 69 | Modified `class` name to minimize CSS code resuse between similar content |
| 76 | Updated closing `</aside>` tag |
| 77 | Modified tag to `<footer>` to improve semantics; removed `class` attribute as it was no longer neccessary |
| 82 | Updated closing `</footer>` tag |

### CSS:  `style.css`

#### Highlights

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
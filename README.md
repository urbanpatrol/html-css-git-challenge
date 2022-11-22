# Weekly Challenge 1

## HTML CSS Git Challenge: Horiseon Website Code Refactor

## Contents
* [Description](#description)
* [Approach](#approach)
* [Challenges](#challenges)

## Description

The client approached me to refactor the code on their Horiseon website to ensure their codebase meets accessibility standards and the site is optimised for search engines.

### User Story
>**AS A** marketing agency
**I WANT** a codebase that follows accessibility standards
**SO THAT** our own site is optimised for search engines

## Approach
I took the following approach in reviewing the codebase adding, subtracting and amending elements. 
* Semantic HTML elements - to give the code more structure and to make it easier to find items for future use. The following elements were introduced header, nav, article, aside and footer. This is used ultimately to help accessibility readers and search engines identify areas of content. 
* Reviewing and amending as required the logical structure of HTML elements ensuring integrity.
* Ensuring that the image and icon elements contain accessible 'alt' attributes as best practice for accessibility.
* Reviewing the heading attributes thereby ensuring they follow sequentially.
* Ensuring all elements are clear and concise and carry a descriptive title where applicable.

## Challenges
#### *Semantic HTML*
Despite many years of working with websites, this is the first time I had been exposed to the concept of Semantic HTML. It took additional research to appreciate and at first I struggled with where to begin. Through trial and error attempts later, it started falling into place 👍  

A good example is the 'nav' element. I was tempted to include all related div tags but thsi broke the codebase and later identified that it should only inclide the actual links/elements in the navigation.

![](challenge/starter/assets/images/horiseon-nav.png)

I found the following resources very helpful:
* [SEMRush Blog - Sematic HTML5 Guide](https://www.semrush.com/blog/semantic-html5-guide/)
* [W3School Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp)

#### *CSS*
I found the CSS to be an easier task where a number of elements had been introduced that were unnecessary. For example, references to font sizing when h2 tags had already been introduded in the HTML.

There were also a number of the same code references to different classes and so it stands to reason to group these for better management.

The following was a helpful resource:
* [W3School CSS Tutorial](https://www.w3schools.com/css/)

## Credits

* Many thanks to Laura, Dan and the TA's for their exceptional patience.
* StackOverflow is an invaluable resource.
* W3School - like wow! - to whomever puts that all together.
* ...and I'm sure there are many others that have got me through Week 1 - thank you all. 

## License

n/a

## Features

The website has no crazy features to speak of, just a simple navigation to various content areas.

## Tests

Finally in both HTML and CSS, as well as my own review for integrity, I used the [W3.org Validator](https://validator.w3.org) to validate code and identify errors. Additionally, I used [Code Beautify](https://codebeautify.org/htmlviewer) to clean up the HTML in terms of layout. 

---

© 2022 Ramon Fritz. Confidential and Proprietary. All Rights Reserved.
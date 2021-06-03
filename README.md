# SEO-landing-page

This is a landing page of a SEO marketing company.
The starter files were given but they needed to be refactored for best HTML and CSS practices. The refactoring includes:

- Semantic HTML
- Ordered Headings
- Streamline CSS to reduce redundancies
- Descriptive Alt tags for images
- Proper Title

![animated gif](./assets/readme-images/page-gif.gif)

## Table of Contents

|                                           |                                                               |                                                    |
| :---------------------------------------: | :-----------------------------------------------------------: | :------------------------------------------------: |
| [Project Introduction](#SEO-landing-page) |            [Table of Contents](#table-of-contents)            | [Development Highlights](#development-hightlights) |
|          [Deployment](#deployed)          | [Description of Page Building](#Description-of-Page-Building) |       [Code Hightlights](#code-hightlights)        |
|  [Technologies Used](#Technologies-Used)  |                      [Credits](#Credits)                      |                [License](#License)                 |

## Development Hightlights

- Refactored exisiting code for best HTML and CSS practices
- Semantic HTML
- Reduce repetitive CSS Code

## Deployed

[Deployment](https://anusontarangkul.github.io/SEO-landing-page/)

This app is deployed using GitHub pages.

## Description of Page Building

- assets
  - CSS for app
  - Images for app
  - README gif
- gitignore
- index
- README
- LICENSE

## Code Highlights

Each sectionhas a class of "service" to streamline CSS styling rather than using an individual styling fore each section tag.

```HTML
    <section id="search-engine-optimization" class="service">
        <img
          src="./assets/images/search-engine-optimization.jpg"
          alt="a notebook that shows a page about the benefits of SEO"
          class="float-left"
        />
        <h2>Search Engine Optimization</h2>
        <p>
          The dominance of mobile internet use means that users are searching
          for the right business as they travel, shop, or sit on their couch at
          home. Search Engine Optimization (SEO) allows you to increase your
          visibility and find the right customers for your business.
        </p>
    </section>
```

Provided descriptive alt tags for images.

```HTML

    <h3>Brand Awareness</h3>
    <img
        src="./assets/images/brand-awareness.png"
        alt="black icon of a person with a lightbulb as a head radiating energy"
    />
```

## Technologies Used

- HTML
- CSS

## Credits

|                           |                                                                                                                                                                                                       |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **David Anusontarangkul** | [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/anusontarangkul/) [![GitHub](https://i.stack.imgur.com/tskMh.png) GitHub](https://github.com/anusontarangkul) |

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

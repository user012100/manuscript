# [Project 1: Manuscript](https://user012100.github.io/manuscript/)

A project responding to [Chapter 16](https://archive.org/details/interaction-of-color-50th-anniversary-edition/page/38/mode/2up) of Interaction of Color by Josef Albers, involving typesetting and replying to the text as a web page.

## Part 1: Semantic Dom

Changes in this part:

*   Created `index.html` in the main repository.
*   Added `html` tag.
*   Added `title` tag within the `head` element.
*   Added semantic elements like `header`, `nav`, `main`, `article`, `footer` within the `body` element.
*   Added main text wrapped in a `p` tag.
*   Added `h1`, `h2`, `h3` and `h4` tags to define headings.
*   Added `br` tags to main text.
*   Added an unordered list to part of main text using `ul` and `li` tags.
*   Added fractions using Unicode.
*   Added `em` tag to emphasize certain words.
*   Added my response to the text.
*   Added IDs for the 2 articles and added relative URLs to the `nav` links using `ID` attribute in the `a` tag.
*   Added an external link to the original text using an absolute URL in the `a` tag.
*   Created `README.md` and `LICENSE.md` in the main repository.

Additional changes after [feedback #1](https://github.com/user012100/manuscript/issues/1):

*   Removed `br` tags from main text.
*   Wrapped every paragraph individually using `p` tag.
*   Added copyright symbol to footer using Unicode.
*   Removed `h2` and reordered headings (now there is only `h1`, `h2`, `h3`).
*   Added `aside` element for chapter and page number markers, with `a` links that direct to the specific page.
*   Moved the link to the original text from `main` to `footer`, added appendix using `details` and `summary` with `a` links to the course site and original text.

## Part 2: Styled Markup

Changes in this part:

*   Added a [CSS reset stylesheet](https://github.com/elad2412/the-new-css-reset) named `reset.css` to reset user-agent styles.
*   Created `style.css` in the main repository.
*   Imported [Outfit font family](https://fonts.google.com/specimen/Outfit) from Google Fonts using `@import`.
*   Changed `body`background color to `#FAFAFA`.
*   Added base styles for the `body`, including `font-family`, `font-weight`, `font-size`, `padding`, `line-height`.
*   Added different `font-weight`, `font-size`, `color` for `h1`, `h2`, `h3`.
*   Added paragraph breaks using `margin-block-start` for `p` and other elements.
*   Changed `max-width` of text in `p` to be limited to 60 characters.
*   Added `font-weight` and `color` to `footer`, `summary` and `a` as well as different colors for `summary:hover` and `a:hover`.
*   Added indentation for `ul` using `padding-left`.
*   Added some `em` tags and classes to certain elements in `index.html`.
*   Changed `color` of `em` tags using classes.
*   Added `text-decoration` styles to underlined elements.
*   Added `background-color` and `padding` to certain number blocks.
*   Changed font to web-safe Geneva in emphasized number blocks due to Unicode fractions not displaying properly using Outfit font.

## Part 3: Spacing and Refinement

Changes in this part, after [feedback #2](https://github.com/user012100/manuscript/issues/2):

*   Changed `:root` font size to `133%`.
*   Removed redundant `em` tags.
*   Added margins and padding to all semantic elements with relative units using `margin-block`, `margin-inline`, `padding-block`, `padding-inline`, etc.
*   Added `span` and `br` tags to `h1` to separate lines using `span:nth-child()`.
*   Made `nav` style `display: fixed`.
*   Adjusted `line-height`for all text elements like `p`, `aside p`, etc.
*   Changed `footer` layout to display items horizontally.
*   Changed the links' visual style to be highlighted.
*   Replaced underlined emphasis in text with colored text.
*   Changed `README.md` from HTML to Markdown.
*   Used `display: flex` for contents of `details` element to display horizontally.

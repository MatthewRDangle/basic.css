# Basic.css
Reduce the amount of unique CSS properties by establishing a cross-browser compatible CSS system for commonly used properties.

## How does it work?
Basic.css groups together commonly used HTML tags (e.g. body, h1, h5, span, button, input, ::selection, ect.) to create fundemental controls for CSS systems such as Themes, Responsive Fonts, Standardize Forms, and more. These controls establish a bedrock layer to build from and removes the reliance of user agent stylesheets. The initial install of basic.css acts similar to Normalize.css or Reset CSS, except basic.css is designed to be customized.

## Is Basic.css for you?
Basic.css establishes a foundation for your stylesheet by removing it's dependency on user agent stylesheets. This similar to Normalize.css and Reset CSS, except they are not designed to be changed, while basic.css is.

Basic.css is for you if:
* Your framework or stylesheet has no foundation on basic selectors (div, button, input, ::selection).
* You desire control over basic selectors
* Your starting a CSS framework from scratch.

Basic.css is not for you if:
* You are using Bootstrap or another framework which already has a foundation built on basic selectors.
* You don't desire control over basic selectors.

## Browser Compatibility
| Property Group | IE | Edge | Chrome | Firefox | Safari |
|:-------------- |:--:|:----:|:------:|:-------:|:------:|
| Theme          |X   |X     |X       |X        |X       |
| Font Sizing    |X   |X     |X       |X        |X       |
| Anchors        |X   |X     |X       |X        |X       |
| Blockquote     |X   |X     |X       |X        |X       |
| User Selection |X   |X     |X       |X        |X       |
| Scrollbar      |    |      |X       |         |X       |
| Lists          |X   |X     |X       |X        |X       |
| Form Element   |X   |X     |X       |X        |X       |
| Table Control  |X   |X     |X       |X        |X       |

## Development
Basic.css is designed to aid the development of websites and webapps through simplicity. To develop for this project requires no prerequsites. Just knowledge of raw CSS.

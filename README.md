# Basic.css
Reduce the amount of unique CSS properties by establishing a cross-browser compatible reusable CSS system for commonly used properties.

## How does it work?
Basic.css groups together commonly used HTML tags (e.g. body,h1, h5, span, button, input, ::selection, ect.) to establish fundemental controls such as Font Sizing, Form Contruction, Links, Highlights and more. This establishes the ground work so commonly used CSS can be quickly modified with one or two properties at the start of the document. The changes are applied instantly through CSS inheritance. 

For example, instead of adjucing font-sizes for each implementation, basic.css font properties sets this once. Once base font size, and once for each header controlled by em's.

## Is Basic.css for you?
Basic.css establishes a CSS foundation between the browser's user-agent and your framework. Basic.css is not Normalize.css or Reset CSS. 

Basic.css is for you if:
* Your framework or stylesheet has no foundation on basic selectors (div, button, input, ::selection).
* You desire control over basic selectors
* Your starting a CSS framework from scratch.
* You are writing a framework based off of BEM (Block, Element, Modifier Architecture).

Basic.css is not for you if:
* You are using Bootstrap or another framework which already has a foundation built on basic selectors.
* You don't desire control over basic selectors.

## Development
Basic.css is designed to aid the development of websites and webapps through simplicity. To develop for this project requires no prerequsites. Just knowledge of raw CSS.

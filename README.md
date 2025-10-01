# Static webpage using HTML + CSS

A simple, responsive site built with simple HTML and vanilla CSS (no frameworks).

## Project Structure


## naming convention: 

**id** = unique hook for ARIA/links/JS.
**class** = styling (BEM). Keep both only when you need both.


**Blocks**: hero, cards, card, contact, nav, site-header
**Elements**: hero__image, cards__list, card__title, contact__link
**Modifiers**: card--featured
**IDs** are for in-page links: #hero, #cards, #contacts 

**nav** = the block: the whole navigation component
**nav__item** = an element: the list item <li> that controls the layout (spacing, positioning, dropdown anchor)
**nav__link** = an element: the clickbait link <a> that controls visuals and interactions(color, hover, focus)

**aria-label**: gives an element an invisible name directly in the attribute.
**aria-labelledby**: points to another element’s text (by id) to use as the name.







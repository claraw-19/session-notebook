## Type selector

A selects all elements of type `A`.

> 'div' selects all `<div>` elementes

## Id selector

Selects all elements with specific id.

You can combine id-selectors with type-selector.

> `#cool` selects any element with `id="cool"`

> `ul #long` selects `<ul id="long">`

## Descendant selector

`A B` selects all `B` inside of `A`.

> `p strong` selects all `strong`elements that are inside of `<p>`.

> `#fancy span` selects any `<span>`elements that are inside of the element with `ìd="fancy"`.

## Class selector

Selects elements by their class `.classname`.

Elements can only have one id, but many classes.

> `.neato` selects all elements with `class="neato"`.

You can combine the class selector with other selectors, like the type selector.

> `ul .important` selects all `<ul>` elements that have `class="important"`.

## Comma combinator

`A, B` selects all `A` and `B` elements.

> `p, .fun` selects all `<p>` elements as well as all elements with 'class="fun"'.

## Universal selector

`*`selects all elements

Combine the universal selector `A *`. This selects every element inside of `A`.

> `p *` selects any element inside all `<p>` elements.

## Adjacent sibling selector

`A+B` selects all `B` elements that directly follow `A`.

> `p + .intro` selects every element with `class="intro"` that directly follows a `p`

> `div + a` selects every `a` element that directly follows a `div`

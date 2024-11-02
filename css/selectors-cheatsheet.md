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

## General sibling selector

`A ~ B` selects all siblings of an element that follow it.

> `A ~ B` selects all `B` that follow a `A`

## Child selector

`A > B` selects direct children of an element.

> `A > B` selects all `B` that are a direct children `A`

## First child pseudo-selector

`:first-child` selects a first child element inside of another element.

> `:first-child` selects all first child elements

> `p:first-child` selects all first child `<p>` elements.

You can combine this pseudo-selector with other selectors.

> `div p:first-child` selects all first child `<p>` elements that are in a `<div>`.

## Only child pseudo-selector

`:only-child` selects any element that is the only element inside of another one.

> `span:only-child` selects the `<span>` elements that are the only child of some other element.

> `ul li:only-child` selects the only `<li>` element that are in a `<ul>`.

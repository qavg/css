# CSS REVIEW

### Element's Tag Type: Selects all elements of that tag type

`div`, `p`, `ul`, etc

### ID Selector: Select elements with an ID

`#id`

### Descendant Selector: Select an element inside another element

`A B`: Selects all B inside of A. B is called a descendant because it is inside of another element

### Combine the Descendant & ID Selectors:

`#id A`: Selects all A inside of #id

### Class Selector: Select elements by their class

`.classname`: `.neato` selects all elements with `class="neato"`

### Combine the Class Selector: You can combine the class selector with other selectors, like the type selector.

`A.className`:
`ul.important` selects all `ul` elements that have `class="important"`
`#big.wide` selects all elements with `id="big"` that also have `class="wide"`

### Combine Descendant, ID, and Class Selectors:

`#fancy.bento orange.small`: selects all small oranges on a fancy bento
(or for each `bento` with `id="fancy"`, selects only `oranges` that have `class="small`")

### Comma Combinator: Combine selectors with commas

`A, B`: Thanks to Shatner technology, this selects all A and B elements. You can combine any selectors this way, and you can specify more than two.

`p`, `.fun` selects all `p` elements as well as all elements with `class="fun"`
`a`, `p`, `div` selects all `a`, `p` and `div` elements
`plate`, `bento` selects everything inside of <plate /> and <bento />, including e.g. <pickle />

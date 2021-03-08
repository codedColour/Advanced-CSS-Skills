# Advanced-CSS-Skills

Importance is considered first. !important | Author declarations | User declaration | then browser default declaration.

 Usually the conflicts arise in author declarations and so the parsing moves on to Specificity.

Specificity precedence is Inline styles (which shouldn't be used) | IDs | Classes, pseudo-classes, attributes | Elements and pseudo-elements

Score as n|n|n|n where n is the number of each case that exists in a selector (e.g. nav#nav div.bold .button scores 0|1|2|2). You then work from left to right. A single inline style will outweigh a dozen IDs for instance, a single ID will outweigh a dozen classes, and so on.

If all have the same score then the cascade will then consider the source order and this is why you always put your stylesheet last in the HTML link.
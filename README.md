# Family.styl

Family.styl is the stylus port of [Family.scss](https://github.com/LukyVj/family.scss)

Family.styl is a set of 26 smart stylus mixins which will help you to manage the style of :nth-child'ified elements, in an easy and classy way.

# Mixins

* `first($num)` — Select all children from the first to `$num`
* `last($num)` — Select all children from the last to `$num`
* `after-first($num)` — Select all children after the first to `$num`
* `from-end($num)` — Select all children before `$num` from the last
* `between($first, $last)` — Select all children between `$first` and `$last`
* `even-between($first, $last)` — Select all even children between `$first` and `$last`
* `odd-between($first, $last)` — Select all odd children between `$first` and `$last`.
* `n-between($num, $first, $last)` — Select all `$num` children between `$first` and `$last`
* `all-but($num)` — Select all children but `$num`
* `each($num)` — Select children each `$num`
* `every($num)` — Alias for `each($num)`
* `from-first-last($num)` — Select the `$num` child from the start and the `$num` child from the last
* `middle($num)` — Select the item in the middle of `$num` child. Only works with odd number chain
* `all-but-first-last($num)` — Select all children between the `$num` first and the `$num` last
* `first-of($limit)` — This quantity-query mixin will only select the first of `$limit` items. It will not work if there is not as much as item as you set in `$limit`
* `last-of($limit)` — This quantity-query mixin will only select the last of `$limit` items. It will not if there is not as much as item as you set in `$limit`
* `at-least($num)` — This quantity-query mixin will select every items if there is at least `$num` items. It will not if there is not as much as item as you set in `$num`
* `at-most($num)` — This quantity-query mixin will select every items if there is at most `$num` items. It will not if there is not as much as item as you set in `$num`
* `inbetween($min, $max)` — This quantity-query mixin will select every items only if there is between `$min` and `$max` items
* `first-child()` — Select the first exact child
* `last-child()` — Select the last exact child
* `even()` — Select all even children
* `odd()` — Select all odd children
* `first-last()` — Select only the first and last child
* `unique()` — Will only select the child if it’s unique
* `only()` — Alias for `unique()`
* `not-unique()` — Will only select children if they are not unique. Meaning if there is at least 2 children, the style is applied
* `child-index($num, $direction = 'forward', $index = 0)` — This mixin is used to automatically sort z-index in numerical order. But it can also sort them in anti-numerical order, depending the parameters you use

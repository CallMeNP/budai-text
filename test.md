# test myst md

## h2
asdf []{#myst-inline-target} asdf

[go](#myst-inline-target)

{ref}`asdf <myst-inline-target>`

(heading-target)=
### Heading

{#paragraph-target}
This is a paragraph, with an `id` attribute.

This is a [span with an `id` attribute]{#span-target}.

:::{note}
:name: directive-target

This is a directive with a `name` option
:::

[reference1](#heading-target), [reference2](#paragraph-target),
[reference3](#span-target), [reference4](#directive-target)
# @smotaal/fragma

Compositional templating primitives.

**What?**

In abstract terms, compositional templating is a methodology for compositional design through recursive breakdown of design features into logically interchangeable units.

In concrete terms, compositional templating refers to document composition relative to the templating constructs of HTML (`<template>` and `<slot>`) and JavaScript (Tagged Templates), decoupled from their encapsulating renditions (ie Components).



**Why?**

Compared to compositional frameworks, which try to devise abstraction layers to simplify and normalize builtin APIs, compositional templating attempts to focus on intuitive ways to directly use those builtins. However, the key underlying principle behind this work is that it does not deal directly with the actual builtins (ie `class extends HTMLTemplatElement {}`) and instead tries to narrow down such DOM-dependent constructs into the more specialized abstractions that are composable without a DOM.

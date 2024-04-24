# Bootcamp-mobu-tutorial

[This](./mobu-tutorial.org) is a brief tutorial describing how to use
Mobu to test Phalanx services.

## Rebuilding the presentation

This presentation is written in Emacs org-mode, and uses the
`org-re-reveal` package to render the presentation outline to
[reveal.js](https://revealjs.com) for presentation.

You will need to have installed the `org-re-reveal` package.  After that,
open the [presentation](./mobu-tutorial.org) and load the rendering
library with `M-x load-library org-re-reveal`.  Once you have done that,
`C-c C-e R R` will generate the presentation as `mobu-tutorial.html`,
which can then be opened in any web browser.


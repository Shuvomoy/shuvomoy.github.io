<!--
Add here global page variables to use throughout your
website.
The website_* must be defined for the RSS to work
-->
@def generate_rss = true
@def website_title = "Shuvomoy Das Gupta"
@def website_descr = "Academic Website"
@def website_url   = "shuvomoy.github.io"

@def author = "Shuvomoy Das Gupta"

@def mintoclevel = 2


<!--
Add here files or directories that should be ignored by Franklin, otherwise
these files might be copied and, if markdown, processed by Franklin which
you might not want. Indicate directories by ending the name with a `/`.
-->
@def ignore = ["node_modules/", "INFORMS_2020_presentation_sozi.html", "MASC-thesis-presentation_sozi.html", "franklin", "franklin.pub"]

@def keep_path = ["google0e64b2a3e84af1d4.html"]

<!--
Add here global latex commands to use throughout your
pages. It can be math commands but does not need to be.
For instance:
* \newcommand{\phrase}{This is a long phrase to copy.}
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}
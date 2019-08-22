# ACM Presentations
ACM presentations given at meetings, talks, or events in
[reveal.js](https://github.com/hakimel/reveal.js/), powerpoint, or other
frameworks.  All of the slides for SIG.com are written using

The master branch is automatically built using GitHub pages and can be viewed
at https://mstacm.github.io/presentations/path/to/directory/.

## Cloning the repository
The presentation repository utilizes the [reveal.js framework](https://revealjs.com/#/)
and in doing so requires it as a submodule. Due to this, cloning the repository
is a little trickier. Please use the following command
```bash
# With SSH
git clone --recursive git@github.com:mstacm/presentations.git

# With HTTPS
git clone --recursive https://github.com/mstacm/presentations.git
```

This will gather all of the necessary presentation files as well as the
submodules recursively.

## Opening a presentation
The easiest way to open a presentation is to open it directly in the
webbrowser or use the command line. For example, let us say the the
`presentations` repo is located at `/home/local/git-local/presentations/`. To
open a meeting presentation you can open your favorite webbrowser and type
`file:///home/local/git-local/presentations/meetings/2018-02-02/index.html`.

Otherwise, you can use the terminal:
```bash
firefox /home/local/git-local/presentations/meetings/2018-02-02/index.html
```

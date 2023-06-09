# Contributing to the Mila Docs

Thank you for your interest into making a better documentation for all at Mila.

Here are some guidelines to help bring your contributions to life.

## What should be included in the Mila Docs

- Mila cluster usage
- Digital Research Alliance of Canada cluster usage
- Job management tips / tricks
- Research good practices
- Software development good practices
- Useful tools

**_NOTE_**: Examples should aim to not consume much more than 1 GPU/hour and 2 CPU/hour

## Issues / Pull Requests

### Issues

Issues can be used to report any error in the documentation, missing or unclear
sections, broken tools or other suggestions to improve the overall
documentation.

### Pull Requests

PRs are welcome and we value the contents of contributions over the appearance
or functionality of the pull request. If you don't know how to write the proper
markup in reStructuredText, simply provide the content you would like to add in
the PR text form which supports markdown or with instructions to format the
content. In the PR, reference the related issues like this:

```
Resolves: #123
See also: #456, #789
```

If you would like to contribute directly in the code of the documentation, keep
the lines width to 80 characters or less. You can attempt to build the docs
yourself to see if the formating is right:

```console
npm i
npm run-script dev
```

All formatting options can be found in the [vitepress](https://vitepress.dev/) documentation.

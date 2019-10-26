# How to Contribute

Any contribution is welcomed, and I hope the community receives this repo well. Below are some guidelines to keep the content across consistent.

## Table of Contents

- [Language of Choice](#language-of-choice)
- [Markdown Guidelines](#markdown-guidelines)
- [Images](#images)
- [Table of Contents](#table-of-contents)
- [Getting Started](#getting-started)
- [Projects](#projects)
- [Docs]()
- [Career Tips]()
- [Resources]()
- [Stories]()
- [Tech Paths]()
- [Tools]()
- [Misc]()

## Language of Choice

The language chosen for introducing programming to newcomers will be javascript. I thought about other scripting languages, but javascript seems to be dominant in both front and backend and can be beneficial to use it for this repo.

Paradigms specific to a language will be placed inside [Language Specific](../Language-Specific/README.md)

## Markdown Guidelines

- The first header will be an H1 with #
- Any subsequent header will be an H2 with ##
- Last header should be an H3 with ###
- Bullet points will be a dash -, not *, or +

## Images

Images should go in the Images folder, and optimized size for web preferably less than 1MB. Images can be inserted with markdown or html if there is a need to change more properties. Images should not be external urls as websites url change, or go away from time to time.

```
<img src="/Images/code.png" width="100" height="100">

![some-image](/Images/code.png)
```

## Table of Contents

For a markdown file a table of contents should be placed at the top as bullet points. Then each bullet point should point to its header.

Example:

```
- [Some topic](some-topic)
- [Another topic](another-topic)

## Some topic
## Another topic
```

## Getting Started

Introductory topics will be rendered in jupyter notebooks to ease the pain of having to do a full setup on a machine. I believe notebooks are the best format since you can have markdown explanations next to code.

## Projects

Basic projects should be used only to emphasize introductory topics.

Intermediate and advanced projects should be as close to a real world application. For now projects should be in javascript, and possible in the future translate to other languages with the help of the community as git submodules.

Guided projects should guide the coder all the way through the project for maximum knowledge goals.

More information on [projects guidelines](Projects.md).
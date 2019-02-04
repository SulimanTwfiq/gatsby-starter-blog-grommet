# Gatsby Starter Blog Grommet

[![Build Status](https://travis-ci.com/Ganevru/gatsby-starter-blog-grommet.svg?branch=master)](https://travis-ci.com/Ganevru/gatsby-starter-blog-grommet)

[GatsbyJS v2](https://www.gatsbyjs.org/) starter for creating a blog. Based on [Grommet v2](https://v2.grommet.io/) UI.

Demo: [https://gatsby-starter-blog-grommet.netlify.com/](https://gatsby-starter-blog-grommet.netlify.com/)

---

## Features

- Easily configurable - see site-config.js in the root
- Switch between grommet themes - dark, base and grommet (default)
- Content/blog folder in the root for blog posts - just write a post in Markdown format taking as an example one of the templates
- Blog posts previews in card style (with a picture-cover or without)
- Responsive Design, optimized for Mobile devices
- Change between light and dark themes
- Sticky Sidebar - [react-sticky](https://github.com/captivationsoftware/react-sticky)

## Technology

- [Gatsby v2](https://www.gatsbyjs.org/) SSG
- [Grommet v2](https://v2.grommet.io/) UI
- [styled-components](https://www.styled-components.com) for style
- [TypeScript](https://typescriptlang.org)
- [ESLint](https://eslint.org/) and [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)
- [lint-staged](https://github.com/okonet/lint-staged) and [husky](https://github.com/typicode/husky) - for linting before commit. It also runs "gatsby build" - this ensures that the site will work after the commit. This makes commits slow, but it helps to avoid mistakes - something that works in gatsby develop may not work in gatsby build. If you do not need this, you can simply delete "husky" settings from package.json.
- [redux](https://redux.js.org/) and [react-redux](https://react-redux.js.org/), example [gatsby using-redux](https://github.com/gatsbyjs/gatsby/tree/master/examples/using-redux)

---

## Prerequisites

The best place to start using Gatsby: [Gatsbyjs.org/tutorial/part-one](https://www.gatsbyjs.org/tutorial/part-one)

Install Gatsby cli (if you have not already):

```text
npm install --global gatsby-cli
```

## Download and install

```text
gatsby new blog-grommet https://github.com/Ganevru/gatsby-starter-blog-grommet
```

```text
cd blog-grommet
```

Running in development:

```text
gatsby develop
```

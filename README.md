# react-github-corners

React wrapper for [GitHub Corners](http://tholman.com/github-corners/) project by [Tim Holman](http://tholman.com/).

[![NPM](https://img.shields.io/npm/v/react-github-corners.svg)](https://www.npmjs.com/package/react-github-corners) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install react-github-corners
```

## Usage

```jsx
import React, { Component } from 'react'

import GitHubCorner from 'react-github-corners'

class Example extends Component {
  render () {
    return (
      <GitHubCorner url='https://github.com/Smoczysko/react-github-corners' />
    )
  }
}
```

### Corner

By default GitHub Corner icon appears in top right corner of the website. You can change that to top left corner using **corner** prop:

```jsx
import React, { Component } from 'react'

import GitHubCorner from 'react-github-corners'

class Example extends Component {
  render () {
    return (
      <GitHubCorner url='https://github.com/Smoczysko/react-github-corners' corner={GitHubCorner.corners.topLeft} />
    )
  }
}
```

### Styling

You can change both **fill** and **color** of the widget by specifying it in props:

```jsx
import React, { Component } from 'react'

import GitHubCorner from 'react-github-corners'

class Example extends Component {
  render () {
    return (
      <GitHubCorner url='https://github.com/Smoczysko/react-github-corners' color='#fff' fill='#70B7FD' />
    )
  }
}
```

### Label

You can change default link label ('View source on GitHub') using **label** prop:

```jsx
import React, { Component } from 'react'

import GitHubCorner from 'react-github-corners'

class Example extends Component {
  render () {
    return (
      <GitHubCorner url='https://github.com/Smoczysko/react-github-corners' label='Come and see us on GitHub!' />
    )
  }
}
```

## License

MIT © [Smoczysko](https://github.com/Smoczysko)

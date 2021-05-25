# @africasokoni/react-flip-countdown

> The React Flip Countdown Component.

[![NPM Version][npm-image]][npm-url]
[![NPM Downloads][downloads-image]][downloads-url]
[![JavaScript Style Guide][coding-image]][coding-url]

[DEMO](https://africasokoni.github.io/react-flip-countdown/)

## Install

Using npm:

```bash
npm install @africasokoni/react-flip-countdown
```

Using yarn:

```bash
yarn add @africasokoni/react-flip-countdown
```

## Usage

### Basic

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleBasic extends Component {
  render() {
    return (
      <FlipCountdown
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### Size

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleSize extends Component {
  render() {
    return (
      <FlipCountdown
        size='large' // Options (Default: medium): large, medium, small, extra-small.
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### Theme

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleTheme extends Component {
  render() {
    return (
      <FlipCountdown
        theme='dark' // Options (Default: dark): dark, light.
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### Title Position

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleTitlePosition extends Component {
  render() {
    return (
      <FlipCountdown
        titlePosition='top' // Options (Default: top): top, bottom.
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### Change title

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleChangeTitle extends Component {
  render() {
    return (
      <FlipCountdown
        yearTitle='Year'
        monthTitle='Months'
        dayTitle='Days'
        hourTitle='Hours'
        minuteTitle='Minutes'
        secondTitle='Seconds'
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### Hide certain sections

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleHideSection extends Component {
  render() {
    return (
      <FlipCountdown
        hideYear
        hideMonth
        hideDay
        // hideHour
        // hideMinute
        // hideSecond
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

### End as Zero

```jsx
import React, { Component } from 'react';

import FlipCountdown from '@africasokoni/react-flip-countdown';

class ExampleHideSection extends Component {
  render() {
    return (
      <FlipCountdown
        endAtZero
        endAt={'2022-12-12 01:26:58'} // Date/Time
      />
    );
  }
}
```

## License

MIT © [africasokoni](https://github.com/africasokoni)

[npm-image]: https://img.shields.io/npm/v/@africasokoni/react-flip-countdown.svg
[npm-url]: https://npmjs.org/package/@africasokoni/react-flip-countdown
[downloads-image]: https://img.shields.io/npm/dm/@africasokoni/react-flip-countdown.svg
[downloads-url]: https://npmcharts.com/compare/@africasokoni/react-flip-countdown?minimal=true
[coding-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[coding-url]: https://standardjs.com

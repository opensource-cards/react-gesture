# react-gesture

[![Greenkeeper badge](https://badges.greenkeeper.io/andcards/react-gesture.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/andcards/react-gesture.svg?branch=master)](https://travis-ci.org/andcards/react-gesture)
[![npm package](https://badge.fury.io/js/react-gesture.svg)](https://www.npmjs.org/package/react-gesture)
[![Dependency Status](https://david-dm.org/andcards/react-gesture.svg)](https://david-dm.org/andcards/react-gesture)
[![devDependency Status](https://david-dm.org/andcards/react-gesture/dev-status.svg)](https://david-dm.org/andcards/react-gesture#info=devDependencies)
[![peerDependency Status](https://david-dm.org/andcards/react-gesture/peer-status.svg)](https://david-dm.org/andcards/react-gesture#info=peerDependencies)

Web gestures recognizer component for React.

![](https://github.com/andcards/react-gesture/blob/master/demo.gif)

### Installation

```
yarn add react-gesture
```

### API

prop               | type                  | default value
-------------------|-----------------------|--------------
`children`         | `element`             |
`disableClick`     | `bool | func`         |
`flickThreshold`   | `number`              | 0.6
`holdTime`         | `number`              | 400
`swipeThreshold`   | `number`              | 10
`onSwipeUp`        | `func`                |
`onSwipeDown`      | `func`                |
`onSwipeLeft`      | `func`                |
`onSwipeRight`     | `func`                |
`onTap`            | `func`                |
`onClick`          | `func`                |
`onHold`           | `func`                |
`onPinchToZoom`    | `func`                |
`onTouchStart`     | `func`                |
`onTouchMove`      | `func`                |
`onTouchCancel`    | `func`                |
`onTouchEnd`       | `func`                |
`onMouseDown`      | `func`                |
`onMouseMove`      | `func`                |
`onMouseUp`        | `func`                |

### License

MIT

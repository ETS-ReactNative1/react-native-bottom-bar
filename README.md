# <img alt="React Native Bottom Bar" src="https://github.com/WrathChaos/react-native-bottom-bar/blob/master/assets/Screenshots/logo.png" width="275"/>

[![Battle Tested ✅](https://img.shields.io/badge/-Battle--Tested%20%E2%9C%85-03666e?style=for-the-badge)](https://github.com/WrathChaos/react-native-button)

[![Fully customizable, unique shaped bottom bar component for React Native.](https://img.shields.io/badge/-Fully%20customizable%2C%20unique%20shaped%20bottom%20bar%20component%20for%20React%20Native-lightgrey?style=for-the-badge)](https://github.com/WrathChaos/react-native-button)

[![npm version](https://img.shields.io/npm/v/react-native-bottom-bar.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-bottom-bar)
[![npm](https://img.shields.io/npm/dt/react-native-bottom-bar.svg?style=for-the-badge)](https://www.npmjs.com/package/react-native-bottom-bar)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p align="center">
<img alt="React Native Bottom Bar" src="https://github.com/WrathChaos/react-native-bottom-bar/blob/master/assets/Screenshots/original.png" width="49.7%"/>
<img alt="React Native Bottom Bar" src="https://github.com/WrathChaos/react-native-bottom-bar/blob/master/assets/Screenshots/examples.png" width="49.7%"/>
</p>

## Installation

Add the dependency:

### Pure React Native :

```js
npm i react-native-bottom-bar
```

### Expo Version :

```js
"react-native-bottom-bar": "WrathChaos/react-native-bottom-bar#expo"
```

### Peer Dependencies :

You must install these dependencies!

```js
"@freakycoder/react-native-helpers": ">= 1.0.0",
"react-native-androw": ">= 0.0.31",
"react-native-vector-icons": ">= 6.0.0",
"react-native-linear-gradient": ">= 2.4.x",
"react-native-dynamic-vector-icons": ">= x.x.x"
```

## Usage

```jsx
<BottomBar
  style={style}
  shapeColor={shapeColor}
  mainIcon={mainIcon}
  mainIconColor={mainIconColor}
  mainIconGradient={mainIconGradient}
  mainIconComponent={mainIconComponent}
  miniButtonsColor={miniButtonsColor}
  firstIconComponent={firstIconComponent}
  secondIconComponent={secondIconComponent}
  thirdIconComponent={thirdIconComponent}
  fourthIconComponent={fourthIconComponent}
/>
```

### Example Application

- I just shared the example project on Expo, simply run on your device to check what it is:
  [via Expo](https://exp.host/@freakycoder/examples) OR
  [check the code](examples/App.js), and yes! :) all of the images, screenshots are directly taken
  from the this example. Of course, you can simply clone the project and run the example on your own environment.

### Configuration - Props

##### BottomBar:

| Property            |   Type    |                  Default                   | Description                                         |
| ------------------- | :-------: | :----------------------------------------: | --------------------------------------------------- |
| style               |   style   |                 container                  | use this to change the main BottomBar's style       |
| shapeStyle          |   style   |                 bottom:89                  | use this to change the main BottomBar's Shape style |
| shapeColor          |   color   |                  #FBFBFD                   | use this to change the unique shape's color         |
| mainIcon            | component |                    icon                    | changes the main big button's icon type             |
| mainIconColor       |   color   |                  #FFFFFF                   | changes the main big button's icon color            |
| mainIconGradient    |   array   |               blue gradient                | changes the main big button's gradient color        |
| mainIconComponent   | component | MainIconButton(Gradient Icon based button) | Make your own button on the main one                |
| miniButtonsColor    |   color   |                    null                    | changes the mini buttons color with a single prop   |
| firstIconComponent  | component |       MiniButton(simple icon button)       | renders your own component as a first button        |
| secondIconComponent | component |       MiniButton(simple icon button)       | renders your own component as a second button       |
| thirdIconComponent  | component |       MiniButton(simple icon button)       | renders your own component as a third button        |
| fourthIconComponent | component |       MiniButton(simple icon button)       | renders your own component as a fourth button       |
| disableFirstIcon    |  boolean  |                   false                    | disable the first icon button                       |
| disableSecondIcon   |  boolean  |                   false                    | disable the second icon button                      |
| disableThirdIcon    |  boolean  |                   false                    | disable the third icon button                       |
| disableFourthIcon   |  boolean  |                   false                    | disable the fourth icon button                      |

### Credits

Thank you [RN Typography Team](https://github.com/hectahertz/react-native-typography) for the ShowcaseScreen :) It has a great design.

## Author

FreakyCoder, kurayogun@gmail.com

## License

React Native Bottom Bar Library is available under the MIT license. See the LICENSE file for more info.

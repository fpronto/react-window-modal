# react-window-modal [![Build Status](https://travis-ci.org/nik-m2/react-window-modal.svg?branch=master)](https://travis-ci.org/nik-m2/react-window-modal)

<p align="center">
    A modal window element designed to be smooth, clean and user friendly.
    <br>
    Includes many features and <a href="https://github.com/nik-m2/window-modal/blob/master/docs/options.md">options</a>! 
    <br>
    <a href="https://codesandbox.io/s/vnxjnnz1o7"><b>Demo</b></a>
    <br>
    <img src="https://user-images.githubusercontent.com/20328954/54089282-d78e3d00-433d-11e9-802e-5c404283cc4a.png"/>
    <br>
    Feature and improvement <a href="https://github.com/nik-m2/window-modal/issues">suggestions</a> welcome!
</p>

## Features

- Pure JS (Written in TypeScript)
- Designed to be used in vanilla JS, or wrapped by front end frameworks (React, Vue, etc)
- Highly tested
- Movable
- Resizable
- Titles (with icons)
- Minimize
- Close
- Scrollable
- Customizable style (override styles with classnames, may have to use `!important`)
- Many options!

## Setup

<details>
    <summary style="display:inline-block;">
        <b>CDN</b>
    </summary>
    <br/>

```xml
<script src="https://cdn.jsdelivr.net/npm/window-modal/build/index.js"/>
```
    
</details>

<br/>

<details open>
    <summary>
        <b>npm</b>
    </summary>
    <br/>

`npm install react-window-modal`

then

```javascript
const WindowModal = require("react-window-modal");
```

or

```javascript
import WindowModal from "react-window-modal";
```
</details>

## Usage

```jsx
const options = { option: value };

function render(props) {
    return <ModalWindow>contents</ModalWindow
}
```

- [Options](https://github.com/nik-m2/window-modal/blob/master/docs/options.md)
- [Events](https://github.com/nik-m2/window-modal/blob/master/docs/Events.md)
- [WindowModal Class](https://github.com/nik-m2/window-modal/blob/master/docs/WindowModal.md)



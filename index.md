# Vue Github Corners Component

> Tholmans github-corners for VueJS

### Current Version: 1.2.2

## Description

Tholman's great github-corners in a convenient VueJS component

All credits go to [Tholman's Original Repo](http://tholman.com/github-corners/)

## Screenshot

Here's a small screenshot:
![GithubCorner][screenshot]

[screenshot]: https://github.com/Roeefl/vue-github-corners/blob/master/src/Screenshot.png?raw=true "GithubCorner"

## Installation

### For installing this module, run:

```javascript
npm install --save vue-github-corners
```

## Usage

### Importing into your project:

```javascript
import GithubCorner from 'vue-github-corners'
```

**If importing into a .Vue file, don't forget to register the component in your export components**

### Demonstration:

```javascript
<template>
  <div id="app">
    <GithubCorner url='https://github.com/Roeefl/vue-github-corners'></GithubCorner>
  </div>
</template>

<script>
  import Index from './components/content/Index'
  import GithubCorner from 'vue-github-corners'

  export default {
    name: 'app',
    components: {
      Index,
      GithubCorner
    },
...
```

### Basic Example:

```javascript
<GithubCorner url="https://github.com/Roeefl/vue-github-corners"
              :size='120' >
</GithubCorner>
```

### Demonstrating usage of all available attributes:

```javascript
<GithubCorner url="https://github.com/Roeefl/vue-github-corners"
              :size='140'
              cornerColor='#625D5D'
              gitColor='PeachPuff'
              leftCorner
              flipOnHover >
</GithubCorner>
```

## Available Properties

| Property Name | Type | Default Value | Description |
|--------------:|:----:|:-------------:|-------------|
| url | String | '/' | Link to github repo |
| size | Number (v-bind:) | 80 | Determines width & height of corner |
| cornerColor | String | '#625D5D' | Background color for the corner |
| gitColor | String | 'PeachPuff' | Fill color for the octocat |
| leftCorner | Boolean | false | Use leftCorner to have the corner on the left, otherwise it'll be on the right by default |
| flipOnHover | Boolean | false | Use flipOnHover to get a hover color flip affect to add some further life to the component |
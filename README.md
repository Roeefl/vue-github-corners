# vue-github-corners

> Tholmans github-corners for VueJS

### Current Version: 1.2.1

## Description

Tholmans great github-corners in a convenient VueJS component

## Installation

For installing this module, run:
```bash
npm install --save vue-github-corners
```

## Usage

### Basic Example:

```javascript
import GithubCorner from 'vue-github-corners'

<GithubCorner url="https://github.com/Roeefl/vue-github-corners"
              :size='120' >
</GithubCorner>
```

### Demonstrating usage of all available attributes:

```javascript
import GithubCorner from 'vue-github-corners'

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
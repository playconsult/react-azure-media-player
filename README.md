# Intro

This project is a fork of [react-azure-mp](https://github.com/SidKH/react-azure-mp). The forked project seems to be out of maintenance. This project intends to build on its origin repository and extend with new features.

# React Azure media player

[![NPM](https://img.shields.io/npm/v/react-azure-mp.svg)](https://www.npmjs.com/package/react-azure-mp) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
  
React wrapper for the [azure media player](http://ampdemo.azureedge.net/azuremediaplayer.html)

## Install

```bash
npm install --save react-azure-mp
```

## Usage

```jsx
import React from 'react'
import { AzureMP } from 'react-azure-mp'

const Example = () => (
  <AzureMP
     skin="amp-flush"
     src={[{src: "http://amssamples.streaming.mediaservices.windows.net/91492735-c523-432b-ba01-faba6c2206a2/AzureMediaServicesPromo.ism/manifest", type: "application/vnd.ms-sstr+xml" }]}
   />
)
```

## Sandbox examples:
- [Simple initialization](https://codesandbox.io/s/v845rpv0qy)
- [Custom amp options](https://codesandbox.io/s/j7olp9617y)
- [Change player skin](https://codesandbox.io/s/jjxz0qw4l3)
- [Adapt for a different aspect ratio](https://codesandbox.io/s/xv0yj030kw)

## SSR
Supports server-side rendering

## License

Released under same license as origin project (MIT)

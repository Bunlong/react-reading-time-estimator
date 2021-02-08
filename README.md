# react-reading-time-estimator

Medium's like reading time estimator for React.

`react-reading-time-estimator` helps you estimate how long an article will take to read. It works perfectly with plain text.

## 🎁 Features

* Compatible with both JavaScript and TypeScript

## 🔧 Install

react-reading-time-estimator is available on npm. It can be installed with the following command:

```
npm install react-reading-time-estimator --save
```

react-reading-time-estimator is available on yarn as well. It can be installed with the following command:

```
yarn add react-reading-time-estimator
```

## 💡 Usage

```js
import { useReadingTime } from "react-reading-time-estimator";

const {
  text, // 1 min read
  minutes, // 1
  words, // 168
  time, // 0.5309090909090909
} = useReadingTime(text);
```

## 📚 Hook

`useReadingTime(text: string)`
  * `text` – the text to be estimated.

## 💖 Wrap Up

If you think any of the `react-reading-time-estimator` can be improved, please do open a PR with any updates and submit any issues. Also, I will continue to improve this, so you might want to watch/star this repository to revisit.

## 🌟 Contribution

We'd love to have your helping hand on contributions to `react-reading-time-estimator` by forking and sending a pull request!

Your contributions are heartily ♡ welcome, recognized and appreciated. (✿◠‿◠)

How to contribute:

- Open pull request with improvements
- Discuss ideas in issues
- Spread the word
- Reach out with any feedback

## ⚖️ License

The MIT License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<!-- https://raw.githubusercontent.com/bunlong/react-barcodes/master/README/logo.png -->
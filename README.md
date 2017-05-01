# generate gaussian kernel matrix

[![Greenkeeper badge](https://badges.greenkeeper.io/sidorares/gaussian-convolution-kernel.svg)](https://greenkeeper.io/)

```js
var generateGaussianKernel = require('gaussian-convolution-kernel');
var sigma = 2;
var kernel = generateGaussianKernel(5, sigma); // returns flat array, 25 elements
```

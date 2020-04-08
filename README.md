# Human Activity Recognition Research Repository 
> Human Activity Recognition (HAR) Resarch repository

[![NPM Version][npm-image]][npm-url]
[![Build Status][travis-image]][travis-url]
[![Downloads Stats][npm-downloads]][npm-url]

Human activity recognition, or HAR, is a challenging time series classification task.

It involves predicting the movement of a person based on sensor data and traditionally involves deep domain expertise and methods from signal processing to correctly engineer features from the raw data in order to fit a machine learning model.

Recently, deep learning methods such as convolutional neural networks and recurrent neural networks have shown capable and even achieve state-of-the-art results by automatically learning features from the raw sensor data.


![](header.png)

## Installation

OS X & Linux:

```sh
To-Do
```

Windows:

```sh
To-Do
```

## HAR AI Models

After reading this post, you will know:

* Activity recognition is the problem of predicting the movement of a person, often indoors, based on sensor data, such as an accelerometer in a smartphone.
* Streams of sensor data are often split into subs-sequences called windows, and each window is associated with a broader activity, called a sliding window approach.
* Convolutional neural networks and long short-term memory networks, and perhaps both together, are best suited to learning features from raw sensor data and predicting the associated movement.


_For more examples and usage, please refer to the [Wiki][wiki]._

## Development setup

Describe how to install all development dependencies and how to run an automated test-suite of some kind. Potentially do this for multiple platforms.

```sh
run install.bat
```

## Release History

Major,Minor,Bug

* 0.0.0
    * Work in progress

## Contact

Ümit Mert ÇAĞLAR – [@YourTwitter](https://twitter.com/dbader_org) – mert.caglar@metu.edu.tr

Distributed under the MIT license. See ``LICENSE`` for more information.

[https://github.com/caglarmert/HAR-Research](https://github.com/dbader/)

## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

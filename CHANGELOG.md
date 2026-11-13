# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.3.3](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.3.2...1.3.3) (2026-11-13)


### Bug Fixes

* **widget:** leave a dead order on a refused payment ([f8908ab](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/f8908abdd0de9d42938bc845d141603a497e19ea))

### [1.3.2](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.3.1...1.3.2) (2026-07-10)


### Bug Fixes

* **widget:** preserve the customer cart on a failed payment ([defa1be](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/defa1bead93c73b21ab12535ae25ab538e468b37))
* **widget:** qualify \Payline\PaylineSDK::ERR_CODE to avoid a fatal ([c4db710](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/c4db710e90c3d79d9cb410f96b302282dfff1e34))
* **widget:** send return/cancel URLs in doWebPayment payload ([0ebeecd](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/0ebeecd4c5c28ff224e78afe0b4d5bd3865818e4))
* **widget:** throw instead of calling _critical() on the Helper ([6ca5d79](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/6ca5d79e7bccc7c6ca5d0343bd6da310c4ed1665))

### [1.3.1](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.3.0...1.3.1) (2021-10-29)


### Bug Fixes

* **notification:** prevent unsupported server notifications ([ad4fcd9](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/ad4fcd96ddea6b1b9e585a6f4330842ecece2c25))

## [1.3.0](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.2.2...1.3.0) (2021-10-13)


### Features

* **config:** expose the environment config as a FC config ([ee80064](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/ee8006458ecaa40350fbed4b44dd1f997aa2dfed))

### [1.2.2](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.2.1...1.2.2) (2021-10-13)


### Bug Fixes

* **wallet:** use correct class properties for wallet ([51b4f5d](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/51b4f5dd810209d01994df0cf13bd2b9ed54a698))

### [1.2.1](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.2.0...1.2.1) (2021-06-03)


### Bug Fixes

* **url:** use correct Front-Commerce url for frontend redirection ([ceb3ec4](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/ceb3ec4c0ec31a2338c5c74d28bfe1bc71f6e978))

## [1.2.0](https://github.com/front-commerce/magento1-module-payline-front-commerce/compare/1.1.0...1.2.0) (2021-04-01)


### Features

* check status and return result codes when placing an order ([ae78423](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/ae78423c28d4405c5b3e3dc5103e3c903c87cae6))

## 1.1.0 (2021-03-12)


### Features

* **api:** add endpoints to generate a token and place order ([4c5c2c2](https://github.com/front-commerce/magento1-module-payline-front-commerce/commit/4c5c2c2063c4632dbb11a2cc978f68853cae52df))

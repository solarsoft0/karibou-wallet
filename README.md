## Main usage
The purpose of this project is to provide a simple and intiutive API to handle a simple Wallet manager for your e-commerce. It has bean designed to work on server side.


## Installation
From github,    

    git clone https://github.com/evaletolab/karibou-wallet
    cd karibou-wallet

Easiest way to install karibou-wallet is by using npm *(not yet ready for production)*:

    npm install --save karibou-wallet


## Running unit tests

To run unit tests you need [Mocha](https://github.com/visionmedia/mocha),
and [should.js](https://github.com/visionmedia/should.js). The tests are run simply by simply typing:

    NODE_ENV=test ./node_modules/.bin/mocha

Do not run tests with your live processor. Make sure you are running in a
sandbox.


##Overview
When using the karibou-wallet api, you basically deal with 3 separate concepts: 
- wallet (the container of an amount of money),
 - wallet can be a giftcard, it's a kind of floating wallet, it has been designed to be transfered in to a personal wallet
- transaction (helper to manage charges)
- transfer (helper to transfer money from/to BANK/Wallet)



## License
The API is available under AGPL V3 to protect the long term interests of the community – you are free to use it with no restrictions but if you change the server code, then those code changes must be contributed back.

> Copyright (c) 2014 Olivier Evalet (http://evaletolab.ch/)<br/>
> <br/><br/>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the “Software”), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
> <br/>
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
> <br/>
> THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.

# Blockchain Data

Blockchain has the potential to change the way that the world approaches data. Develop Blockchain skills by understanding the data model behind Blockchain by developing your own simplified private blockchain.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Installing Node and NPM is pretty straightforward using the installer package available from the (Node.js® web site)[https://nodejs.org/en/].

### Configuring your project

- Install crypto-js with --save flag to save dependency to our package.json file
```
npm install crypto-js --save
```
- Install level with --save flag
```
npm install level --save
```

## Testing

To test code:
1: Open the file simpleChain.js
2: At the end of the file you will find the call to the test() function.
3: First parameter: true if you want to performe the test; pro default true
4: Second parameter: number of block in the chain; pro default 10
5: Thirs parameter: the block in which you want an error be induced: pro default [2,4,7]
```
node simpleChain.js
```

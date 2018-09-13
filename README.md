# Blockchain Data

Blockchain has the potential to change the way that the world approaches data. Develop Blockchain skills by understanding the data model behind Blockchain by developing your own simplified private blockchain.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Installing Node and NPM is pretty straightforward using the installer package available from the (Node.js® web site)[https://nodejs.org/en/].

### Configuring your project

- Clone the repository in your local environment
```
git clone <url GitHuib Repo>
```
- Go to the project folder
```
cd <project name>
```
- Install the dependencies (crypto-js and level)
```
npm install
```

## Testing

To test code:
- Open the file simpleChain.js
- At the end of the file you will find the call to the test() function.
- First parameter: true if you want to performe the test; pro default true
- Second parameter: number of block in the chain; pro default 10
- Thirs parameter: the block in which you want an error be induced: pro default [2,4,7]
```
node simpleChain.js
```

# amplify-and-jest-sample
This is a sample app that demonstrates Amplify and Jest not playing well
together with (mostly) out of the box default settings.

### Environment
1. Node version: 11.5.0
1. NPM version: 6.7.0
1. Mac OS Mojave 10.14.2
1. Expo version: 2.10.1

### Reproducing this problem
```bash
git clone git@github.com:josephbridgwaterrowe/amplify-and-jest-sample.git
cd amplify-and-jest-sample
git checkout 1-amplify-and-jest-fail-redux
npm install
npm test
```

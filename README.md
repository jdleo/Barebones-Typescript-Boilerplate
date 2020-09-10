# Barebones Typescript Boilerplate

This is the bare minimum that I personally need to get going with a Typescript project. It includes babel, node types, typescript, and ts-node + nodemon in dev dependencies to get going quickly. Also uses Jest for testing.

### Clone & Install Dependencies

```
git clone git@github.com:jdleo/Barebones-Typescript-Boilerplate.git
cd Barebones-Typescript-Boilerplate
yarn
```

### Start

Running the following will have nodemon watch over `src/main.ts`:

```
yarn start
```

### Test

Running the following will run all tests in `tests/`

```
yarn test
```

### Remove Git Reference

You can now do the following to de-init git (so you can use this boilerplate as your own):

```
rm -rf .git
git init
```

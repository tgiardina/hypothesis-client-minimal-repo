# hypothesis-client-minimal-repo
Minimal repo example for "Error: Cannot find module 'jquery'" bug.

## Setup

There are two branches, "master" and "working-example". "master" shows off the jquery bug while "working-example" shows how to make things work in a dev env.

### master

```
cd client
make build
yarn link
cd ../react-app
yarn link hypothesis
yarn start
```

### working-example

In one terminal:

```
cd client
make dev
```

In another:

```
cd react-app
yarn start
```

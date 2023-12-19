# Hello world action
The action will print "Hello, world" 

# Examples
Here's an example workflow that uses the Hello world action.  The workflow is triggered by a `PUSH` event.

```
name: hello-world

on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v1
    - uses: christina-au/hello-world-action@master

```

# First-work-flow name: Lesson 1

on:
  push:

jobs:
  hello:
    runs-on: ubuntu-latest

    steps:
      - run: echo "Robot is awake!"

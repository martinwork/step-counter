# Step Counter

## Step 1 @unplugged

Let's count some steps!

## Step 2

Make a variable called `||steps||` and set it to zero in on start 

```blocks
let steps = 0
steps = 0
```

## Step 3

Add an ``||input:on shake||`` handler

```blocks
input.onGesture(Gesture.Shake, function () {
})
let steps = 0
steps = 0
```

## Step 4

In the ``||input:on shake||`` handler, change `||steps||` by 1

```blocks
input.onGesture(Gesture.Shake, function () {
    steps += 1
})
let steps = 0
steps = 0
```

## Step 5

In the ``||input:on shake||`` handler, add ``||basic.show number 0||``

```blocks
input.onGesture(Gesture.Shake, function () {
    steps += 1
    basic.showNumber(0)
})
let steps = 0
steps = 0
```

## Step 6

In ``||basic.show number 0||``, change 0 to `||steps||`

```blocks
input.onGesture(Gesture.Shake, function () {
    steps += 1
    basic.showNumber(steps)
})
let steps = 0
steps = 0
```


## Step 7

That's it! Download it to the micro:bit.


> Open this page at [https://martinwork.github.io/step-counter/](https://martinwork.github.io/step-counter/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/martinwork/step-counter** and import

## Edit this project ![Build status badge](https://github.com/martinwork/step-counter/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/martinwork/step-counter** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/martinwork/step-counter/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

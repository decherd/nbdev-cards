nbdev-cards
================

<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

A deck of cards demo of [nbdev](https://nbdev.fast.ai) based on ideas
from [Think Python](https://www.google.com)

## Install

Install using:

    pip install nbdev_cards

or

    conda install -c fastai nbdev_cards

## How to use

This lib provides a
[`Card`](https://decherd.github.io/nbdev-cards/card.html#card) class you
can use to create, display, and compare playing cards:

``` python
Card(1,0), Card(1,1), Card(1, 2), Card(1, 3)
```

    (A♣️, A♦️, A❤️, A♠️)

Suits are numbered according to this list:

``` python
suits
```

    ['♣️', '♦️', '❤️', '♠️']

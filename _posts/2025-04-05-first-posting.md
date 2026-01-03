---
layout: single
title:  "welcome new world"
categories: coding
tag: [python, blog, jekyll]
---

# 제 첫 게시글입니다.
깃허브 연동 테스트 중.... <br> 여기에 취미생활을 앞으로 올릴 예정입니다.

```python
# Python program to shuffle a deck of card

# importing modules
import itertools, random

# make a deck of cards
deck = list(itertools.product(range(1,14),['Spade','Heart','Diamond','Club']))

# shuffle the cards
random.shuffle(deck)

# draw five cards
print("You got:")
for i in range(5):
   print(deck[i][0], "of", deck[i][1])

```
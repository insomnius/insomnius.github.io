---
title: Golang Generic for Value to Pointer Function
comments: true
categories:
- golang
layout: post
date: '2022-12-16 23:00:00 +0700'
image_header: /assets/uUy2hcEeUBUzpB2avIU9bM9u8Gt2-g693in3.jpeg
---

![Golang Generic](/assets/uUy2hcEeUBUzpB2avIU9bM9u8Gt2-g693in3.jpeg)

Generic type in golang is a way of writing code that allows for the same type of code to be reused without having to write out the same code multiple times. This is done by creating a single function or type that can be used for multiple types of data that are similar in nature. It can be used to simplify code and increase code readability.

One of the use case which I recently found useful is to convert a value into pointer, before generic comes I usually write this kind of function repetitively per type for example:

<code data-gist-id="9aa38a3017c597ea5c293b5b27a7444c" data-gist-line="38-82"></code>

But with generic, I only have to write two functions:

<code data-gist-id="9aa38a3017c597ea5c293b5b27a7444c" data-gist-line="84-93"></code>

This makes development faster and more efficient, as developers don't have to write and maintain separate code for each type of data. With generics, developers can create code that works for any type of data, allowing for greater flexibility and scalability. Imagine the possibilities of generic types in Golang, and how it can help developers write better code more quickly.

![magic meme gif](/assets/magic-meme.gif)

**NOTES: To use generic you should have atleast golang with version 1.18**

For full code example you could visit this gist [HERE](https://gist.github.com/insomnius/9aa38a3017c597ea5c293b5b27a7444c).

You could also find other example in golang github repository here:

1. https://github.com/golang/exp/tree/master/constraints
2. https://github.com/golang/exp/tree/master/maps
3. https://github.com/golang/exp/tree/master/slices


<script
  type="text/javascript"
  src="/assets/gist-embed.min.js"
></script>
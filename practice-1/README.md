<h1>
  <span class="headline">Python Prework</span>
  <span class="subhead">Python Practice No. 1</span>
</h1>

## Python Practice No. 1 ( 35 min )

_author: [Riley Dallas](https://generalassemb.ly/instructors/riley-dallas/8760) | web developer and data scientist_

----
<br>

When working in data science, you’ll find that you’ll need to use Python to tackle real business problems. We’ve compiled a list of Codewars challenges to help you hone those Python programming skills. Let’s get started!

## Topics

- Codewars Python Challenges

### Learning Objectives

By the end of this lesson, you'll be able to:

- Complete coding challenges using Python.

## Why Codewars?

Throughout this lesson, you’ll be completing challenges in [Codewars](https://www.codewars.com/), a site that’s jam-packed with community-sourced programming challenges ranging in difficulty from easy to very difficult.

Because of their popularity, Codewars challenges are oftentimes used in data science job interviews. So, the benefits you’ll gain from completing them will stay with you beyond the end of DSB (Data Science Bootcamp) as you begin exploring careers in data science.

Another bonus: Once you start solving more challenging problems, your Codewars rank increases. Extra cool points!

## Setting Up Your Codewars Account

*If you already have a Codewars account, go ahead and skip this.

1. Head over to [Codewars](https://www.codewars.com/).
2. Click Sign Up.
3. Select Python as your programming language.
4. Here’s where your practice begins — you’ll need to complete a short challenge to progress to the final registration screen. A hint to help you solve this: Remember that functions should return values.

Give it your best shot!

<a href="https://generalassembly.wistia.com/medias/0kkvof9d2b"><img src="https://embed-ssl.wistia.com/deliveries/25a9d12f64e67898567d27f06ab88f705c103d02.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Navigating Codewars Challenges

In this lesson, you’ll see directions for select Codewars challenges, followed by a walk-through of one of our instructors solving that same challenge.

After you read each set of directions, first try your best to solve the challenge on your own.

Once you’ve attempted it, go ahead and watch the instructor walk-through on the following screen.

Let’s dive in!

## Basic Mathematical Operations Challenge

**Challenge**: [Basic Mathematical Operations](https://www.codewars.com/kata/basic-mathematical-operations)

**Directions**: Create a function that takes these parameters:

- A mathematical operation (i.e., `+`, `-`, `/`, `*` — a string)
- Two numbers

You’ll want to compute results between the two numbers based on this operation:

```python
basic_op('+', 4, 7) 
Output: 11

basic_op('-', 15, 18) 
Output: -3

basic_op('*', 5, 5) 
Output: 25

basic_op('/', 49, 7)
Output: 7
```
    
**Hint**: Create a conditional statement (`if`/`elif`/`else`) that looks at the operation.

## Solution: Basic Mathematical Operations Challenge

<a href="https://generalassembly.wistia.com/medias/sdvdyx96lk"><img src="https://embed-ssl.wistia.com/deliveries/3c454baaaa60f96c5e860c21d68b75c4a041448d.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Sum of Positive Challenge

**Challenge**: [Sum of Positive](https://www.codewars.com/kata/sum-of-positive)

**Directions**: Create a function that adds up all of the positive numbers in a list.

```python
positive_sum([0, 1, 2, 3, -1])
Output: 6

positive_sum([1, -3, 1, 0, 1])
Output: 3
```

**Hint**: You’ll need to `for` loop the list of numbers and run a conditional statement (`if`/`elif`/`else`) for each number.

## Solution: Sum of Positive Challenge

<a href="https://generalassembly.wistia.com/medias/uqkqf4fqb1"><img src="https://embed-ssl.wistia.com/deliveries/9fab2562967bf09306fee8ecbb03454f847f44de.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## String Repeat Challenge

**Challenge**: [String Repeat](https://www.codewars.com/kata/string-repeat)

**Directions**: Write a function that repeats a string n number of times (where n is a positive integer).

```python
repeatStr(6, "I")
Output: IIIIII

repeatStr(3, "Hello")
Output: HelloHelloHello
```

**Hint**: You’ll need to `for` loop using the `range()` function. Start with an empty string and concatenate each time through the loop.

## Solution: String Repeat Challenge

<a href="https://generalassembly.wistia.com/medias/hiohvw7kcu"><img src="https://embed-ssl.wistia.com/deliveries/c21d70913d644dbdfd4448fa92e28265e1ab8138.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Find Maximum and Minimum Values of a List Challenge

**Challenge**: [Find Maximum and Minumum Values of a List](https://www.codewars.com/kata/find-maximum-and-minimum-values-of-a-list)

**Directions**: You’ll want to create two functions. Each will take a list of numbers, and your job is to return the largest or smallest number in said list, depending on which function is being called.

```python
maximum([4,6,2,1,9,63,-134,566])
Output: 566

minimum([-52, 56, 30, 29, -110])
Output: -110
```

**Hint**: There are Python functions that can do this for you. If you don’t know what they are, this is a great opportunity to try out [Stack Overflow](https://stackoverflow.com/).

## Solution: Find Maximum and Minimum Values of a List Challenge

<a href="https://generalassembly.wistia.com/medias/08ehgb4f1d"><img src="https://embed-ssl.wistia.com/deliveries/1f6f4f35fcc19c2eac83b71aee72b72c7317ce3d.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## A Needle in the Haystack Challenge

**Challenge**: [A Needle in the Haystack](https://www.codewars.com/kata/a-needle-in-the-haystack)

**Directions**: You’re given a list of strings. One of those strings is “needle.” Your job is to find the index of where “needle” is in the list.

```python
find_needle(['hay', 'hay', 'hay', 'moreJunk', 'needle'])
Output: "Found the needle at position 4."
```

**Hint**: Google the `enumerate()` function. You may find that it’s a cool thing to learn and use here!

## Solution: A Needle in the Haystack Challenge

<a href="https://generalassembly.wistia.com/medias/9tl6rs3oi1"><img src="https://embed-ssl.wistia.com/deliveries/f2e97c21843e2946527209531421c896bf832719.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Wrap Up

At this point, you’ve used the basic tools of Python — conditionals, functions, loops — to solve programming tasks, and you should feel comfortable with these tools going into the course. Try exploring Codewars to find similar challenges and continue practicing on your own!

## Up Next..

There's one more module in the Python Prework, some more Codewars challenges to get more practice under your belt with some solution walkthroughs.

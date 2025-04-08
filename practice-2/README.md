<h1>
  <span class="headline">Python Prework</span>
  <span class="subhead">Python Practice No. 2</span>
</h1>

## Python Practice No. 2 ( 35 min )

_author: [Riley Dallas](https://generalassemb.ly/instructors/riley-dallas/8760) | web developer and data scientist_

----
<br>

Now that you’ve got some Codewars practice under your belt, we’ll explore some more complex examples in this lesson. Think of these challenges as crossword puzzles for coders. Let’s try them out!

## Topics

- Codewars Python Challenges

### Learning Objectives

By the end of this lesson, you'll be able to:

- Complete coding challenges using Python.

## Reversed Strings Challenge

**Challenge**: [Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018)

**Directions**: Write a function that reverses a string.

```python
solution("Hi mom")

Output: "mom iH"
```

**Hint**: This one is easily google-able. Remember, you’re not expected to know everything as a coder, but you are expected to be able to google your way out of a problem.

## Solution: Reversed Strings Challenge

<a href="https://generalassembly.wistia.com/medias/963lq8ngvr"><img src="https://embed-ssl.wistia.com/deliveries/e80b69cda6724b1b466c934a2fa095a736ee6191.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Sum of Two Lowest Positive Integers Challenge

**Challenge**: [Sum Of Two Lowest Positive Integers](https://www.codewars.com/kata/sum-of-two-lowest-positive-integers/python)

**Directions**: Given a list of numbers, write a function that returns the sum of the two lowest integers.

```python
sum_two_smallest_numbers([19, 5, 42, 2, 77])

Output: 7
```

**Hint**: There’s a function in Python that will automatically sort a list from lowest to highest (i.e., ascending order).

## Solution: Sum of Two Lowest Positive Integers Challenge

<a href="https://generalassembly.wistia.com/medias/mzj5h12r0o"><img src="https://embed-ssl.wistia.com/deliveries/ae9dabb9a5e902de45fb0b12df1d1961c8d3ad26.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Highest and Lowest Challenge

**Challenge**: [Highest and Lowest](https://www.codewars.com/kata/highest-and-lowest/python)

**Directions**: Given a string of numbers (separated by spaces), create a function that returns a string containing the highest and lowest numbers.

```python
high_and_low("1 2 3 4 5")
Output: "5 1"

high_and_low("1 2 -3 4 5")
Output: "5 -3"
```

**Hint**: This one involves several steps:

1. Strings have a `split()` method that chops them into lists of strings.
2. There’s a Python function for turning a string into an integer.

## Solution: Highest and Lowest Challenge

<a href="https://generalassembly.wistia.com/medias/fwx2w7anwt"><img src="https://embed-ssl.wistia.com/deliveries/18116cdcc0bfb02ea77ea8776f102e5220a02873.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Simple Consecutive Pairs Challenge

**Challenge**: [Simple Consecutive Pairs](https://www.codewars.com/kata/simple-consecutive-pairs)

**Directions**: Given a list of numbers, count how many pairs of numbers are consecutive. Note that, in the example below, the pairs are `(1,2)`, `(5,8)`, `(-4,-3)`, etc. Even though they’re next to each other, `2` and `5` are not a pair.

```python
pairs([1,2,5,8,-4,-3,7,6,5])
Output: 3
```

**Note**:
- The pairs are `(1,2)`, `(5,8)`, `(-4,-3)`, `(7,6)`.
- Of the 4 pairs, 3 are consecutive, hence the output.
- The list has an odd number of items, therefore the last number (5) doesn’t have a pair.

**Hint**: Use a for loop with the range() function. Note that the range() function has a third parameter, which is the skip.

## Solution: Simple Consecutive Pairs Challenge

<a href="https://generalassembly.wistia.com/medias/s61ala1e7u"><img src="https://embed-ssl.wistia.com/deliveries/de536042821497719fbbb2986858557ff22e2e43.jpg?image_crop_resized=900x506&image_play_button=true&image_play_button_size=2x&image_play_button_color=222222e0" alt="codewars" width="450" height="253" /></a>

## Summary

The challenges in this lesson ranged from moderately difficult to difficult — congrats to you for giving them a go! If you struggled with some of them, that’s OK! Keep practicing with similar problems in Codewars until you’re able to solve them with confidence.

That wraps up the Python programming prework, continue on to the Math prework.

### Solution by: Kendra Moyars

### Warmup: Fibonacci

The [Fibonacci Sequence](http://en.wikipedia.org/wiki/Fibonacci_number), which sums each number with the one before it, is a great example of a problem that can be solved recursively.

### Assignment 1

<div class="lesson-content__panel" markdown="1">
  1. Write a method `#fibs` which takes a number and returns that many members of the fibonacci sequence.  Use iteration for this solution.
  2. Now write another method `#fibs_rec` which solves the same problem recursively.  This can be done in just 3 lines (or 1 if you're crazy, but don't consider either of these lengths a requirement... just get it done).
</div>

### Project: Merge Sort

We spent some time early on dealing with sorting (e.g. bubble sort).  Now it's time to take another look at sorting with [Merge Sort](http://en.wikipedia.org/wiki/Merge_sort), a type of sort that lends itself well to recursion and can be much faster than bubble sort on the right data sets.  You'll build a method which sorts a given array but uses a "merge sort" method for doing so.

It can be a bit strange to wrap your head around, but just remember you're "dividing and conquering" the problem.

### Background Viewing

The first step is to actually understand what the merge sort algorithm is doing:

1. Check out [this introductory video](http://www.youtube.com/watch?v=EeQ8pwjQxTM) from Harvard's CS50x course.
2. Check out [this more detailed explanation](https://www.youtube.com/watch?v=uEbdK2CG_B8&feature=youtu.be&t=1h2m) by David J. Malan (watch only until 1:14:00).
3. [Merge Sort -- How it Works part 1](https://www.youtube.com/watch?v=OAsokGNa18k) and [Merge Sort -- How it Works part II](http://www.youtube.com/watch?v=nNhpFO9CmPs) on YouTube give you a more formal look at this problem if you're still unclear.

### Assignment 2
<div class="lesson-content__panel" markdown="1">
  1. Build a method `#merge_sort` that takes in an array and returns a sorted array, using a recursive merge sort methodology.
  2. Tips:
      1. Think about what the base case is and what behavior is happening again and again and can actually be delegated to someone else (e.g. that same method!).
      2. It may be helpful to check out the background videos again if you don't quite understand what should be going on.
</div>
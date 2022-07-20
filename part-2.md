# Part - 2

## a. Variables 

## b. Decision

## c. Loop (repetition)

```js
let total = 0;
let count = 1;
while (count <= 1000) {
  total += count;
  count += 1;
}
console.log(total);
// → 55
```



So what's happening here:

The first and second lines give two memory locations their starting values:

 `total` will be used to build up the result of the computation, and `count` will keep track of the number that we are currently looking at.

The keyword `while` is a loop (run a procress till the condition is met and stop).

What is the condition?

`(count <= 10)` same as, `( 1 <= 10)`. Here we are comparing to see whether count is equal to 11 to decide whether it can stop runing. 

Then the block `{ }` that is attached to the `while` construct, what is that? and What is inside that?

`{
  total += count;
  count += 1;
}`

In most of the High-level languages blocks are attached to statements such as `while`, `if`, `for`, `function` etc. It's a syntax thing.

Within the block, the first line of code add the value of `count` to the `total`, and the last line increase `count` by 1 every time the program has decided that `count` is not 11 yet.

This could be also written as:

`{`

`total += count;
  count += 1;
  total = total + count;
  count = count + 1;
}`

count could also be written like this

`{
  total += count;
  count++;
}`

At first the values will be like so:

`0 = 0 + 1`, which will be 1

`1 = 1 + 1`, which will be 2

Let's look in to hood, how the loop is working

| Count | count <= 10 | output |
| ----- | ----------- | ------ |
| 1     | TRUE        | 1      |
| 2     | TRUE        | 2      |
| 3     | TRUE        | 3      |
| 4     | TRUE        | 4      |
| 5     | TRUE        | 5      |
| 6     | TRUE        | 6      |
| 7     | TRUE        | 7      |
| 8     | TRUE        | 8      |
| 9     | TRUE        | 9      |
| 10    | TRUE        | 10     |
| 11    | FALSE       | STOP   |

## d. Functions

## e. Data structures

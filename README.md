# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

*Summary*
1) The function takes some number value and first evaluates `let sum = 0`. 
2) A `for...each` loop occurs and redefines `sum` to be `sum + number**2` , which would be `sum = 0 + number**2`. 
3) The function returns `sum`; however, the `sum` inside `for (number each numbers)` is not in scope.
4) The function will always return `sum = 0`.

```js
function (numbers){
  let sum = 0
  for (number each numbers){
    sum = sum + number**2
  }

  return sum
}
```

| Input | Output |
| ----- | ------ |
| 123   |  0     | 
| 5     |  0     | 
| -3    |  0     | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>The program returns 0 no matter the input.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible

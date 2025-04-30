1. At line 12, '3' is outputted to the console since the length of prices is 3.
2. At line 13, '150' is outputted to the console. Since line 13 is after the for loop, the discountedPrice is equal to the last value in prices (300) * 0.5 (discount), which is 150.
3. At line 14, '150' is outputted to the console. As shown in number 2, the discounted price after the for loop is 150, so finalPrice is (150 * 100) / 100 which is 150 since it doesn't need to be rounded.
4. The function returns a list of the discounted prices, which is [50, 100, 150]. There are 3 prices (100, 200, 300) and a 0.5 discount, so the discounted prices for each of them would be 50, 100, and 150 respectively.
5. There would be an error at line 12 since it calls on i, which is declared with let and only defined within the for loop.
6. Same as number 5, there would be an error at line 13 since discountPrice is declared with let and only definied within the for loop.
7. At line 14, '150' is outputted to the console since the final price of the last item is 150 (300 * 0.5).
8. The function will return a list of the discounted prices, which would be [50, 100, 150]. The for loop calculates the discount price of each item and stores it in the discount list. Since the discount is 0.5 or 50%, the discounted prices would be half of the original prices, so [100/2, 200/2, 300/2] = [50, 100, 150].
9. There would be an error at line 11 since it calls i, which is declared with let and only defined within the for loop.
10. At line 12, '3' would be outputted to the console since the length of the prices list is 3.
11. The function would return [50, 100, 150]. Though it is declared as a constant, since the items are being pushed into the list rather than reassigning 'discounted', a list of discounted prices is returned.
12. A: `student.name`
    B: `student["Grad Year"]`
    C: `student.greeting()`
    D: `student["Favorite Teacher].name`
    E: `student.courseLoad[0]`
13. A: '32'
    B: 1
    C: 3
    D: '3null'
    E: 4
    F: 0
    G: '3undefined'
    H: NaN
14. A: True
    B: False
    C: True
    D: False
    E: False
    F: True
15. The `==` operator compares the values of variables. The `===` operator compares both the values and types of variables.
16. [part2-question16.js](part2-question16.js)
17. When `modifyArray([1,2,3], doSomething)` is called, the following will occurr: An empty array `newArr` will be initialized. For every item in the inputted array (1, 2, 3), the result of the `doSomething` function with the item as input will be pushed into `newArr`. The `doSomething` function doubles the input and returns the value, so [2, 4, 6] would be pushed into `newArr`. Finally, the function would return the array, so the function returns [2, 4, 6].
18. [part2-question18.js](part2-question18.js)
19. The output of the code would be: 
    `1`
    `4`
    `3`
    `2`
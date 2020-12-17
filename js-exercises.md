1. Name all Javascript data types.

2. Explain the difference between reference types and primitives.

3. Create an object of 5 arrays (min-length: 4 strings per array) and destructure the first array in to it's own variables.

4. Destructure the second array with the first and third values only.

5. Swap the 2 values in place from #4 using destructuring.

6. Create a one level deep NESTED array containing 3 values with the nested array containing 2 values. Destructure it.

7. Add a nested object that holds 3 more objects to the object created in #3. Destructure the main keys values of the parent object.

8. Destructure the same keys as #7, renaming them to something else.

9. Destructure the nested object from #7.

10. Create a method on the object that takes in 4 parameters related to the object and destructure them within the method to make it reuseable. Make it have defaults so when called with partial info (even out of order info) it still works. Test it. For reference see js-notes Destrucuring Objects.

11. Spread 2 of the arrays from the object into 1 single array.

12. Create a function that takes in 3 pizza ingredients and console logs them all in a single string. Get all ingredients from an array of 3 prompt calls and store them in a variable. Spread the variable into the function.

13. Create a new object with 2 more key value pairs and spread the previous object into the new one.

14. Shallow copy the newly created array by spreading it into a new 3rd object. Change a property on the newest object and compare to the second. Explain why they are different.

15. Create an array of 5 numbers. Destructure the first 2 into their own variables and the other 3 into 1 variable using the rest operator.

16. Use the rest operator to destucture 2 of the arrays from the first object that are joined using the spread operator.

17. From the nested object in #7, using the rest operator, destructure the first into its own variable and the last 2 into another variable.

18. Create an add function that takes in any amount of arguments by using the rest operator as a param. Set a sum variable to 0. Use a for loop to loop over the arbitrary number of arguments and add them all together. Test it. Create an array of numbers and store it in a variable. Use the new variable in the add function as an argument using the rest operator.

19. What are the falsey values in Javascript? What are the truthy values in Javascript?

20. Use the || operator to short-circuit:

The first truthy value will return. If none, returns last value.

- Console log a number || a string
- Console log an empty string "" || a non-empty string
- Console log a true boolean || 0
- Console log a false boolean || 0
- Console log undefined || null
- Console log undefined || 0 || empty string "" || a non-empty string || a number || null

21. Use the && operator to short-circuit:

The first falsey value will return. If none returns last value.

- Console log 0 && a non-empty string
- Console log a number && a non-empty string

22. Set a property on an object that is 0. Set a variable to equal that property || another number. Why is it not 0?

23. What are the nullish values in Javascript?

24. Use the nullish coalescing operator to ensure we get 0 in #22. 

25. Spread 2 arrays from the 1st object into a variable. Use a for of loop and log each item of the new array.

26. Use a for of loop and the Array.entries method to console log the index AND each item of the array created in #25.

27.
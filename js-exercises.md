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

27. Using the same syntax as #26 add array destructuring to the loop and console log the corresponding index and item for each iteration.

30. Create a variable called weekdays that is an array of strings holding all the days of the week. Create an object called openingHours and set the first 2 keys in the object using enhanced object literals to compute the day of the week using the index of the weekdays array. On the third key use a template literal to do a mathematical operation to compute the number of that day of the week.

31. What is optional chaining and what problem does it solve?

32. Loop over the keys of the object created in #7 and log them.

33. Loop over the values of the objects created in #7 and log them.

34. Loop over the entries of the object created in #7 and log them. What is the difference between Object.entries and Array.entries?

35. What is the main use case of Sets?

36. Create a set out of an array of strings that include duplicate values. Console log the set.

37. Check the size of the set, loop over the set with a for of logging each item,, check to see if the set has a certain value, add a unique string to the set, remove the first string of the set. and clear the whole set.

38. What is a main difference of Maps and Objects?

39. Create a new Map called hotel and set 3 key value pairs.

40. In the hotel Map, get the value of the 1st value through the key, check to see if the a value exists on it, delete the second key/value pair, clear the whole hotel Map.

41. Why should you avoid the delete operator on objects?

42. What type of data structure can you store DOM elements in?

43. Pass 5 key/value pairs into a car Map using an array of arrays when declaring.

44. Use the set method to set an array of arrays as key value pairs. Notice how the key value pairs. Remove the containing array around the arrays and now use the set method with the list of arrays. Notice the key value pairs no matter how many arrays you add.

45. Create an openingHours object with 3 days and open and close times for each (use whole numbers from a 24hr clock ex. 23). Create an hours Map by using Object.entries. Notice that object.entries returns an array of arrays.

46. Spread the hotel map into and array with the hotel.entries. 

47. Convert the hoursMap to an array using the spread operator.

48. What are the 4 main data structures in Javascript?

49. If you have a simple list what data structure should you use?

50. If you have key/value pairs which structure types should you use?

51. If you need an ordered list that may contain duplicates, what data structure should you use?

52. If you have unique values what data structure should you use?

53. What data structure should you use if you need to include functions?

54. If you need to manipulate data, what data structure should you use?

55. If you require high-performance (up to 10x faster than arrays for lookup/delete) which data structure should you use?

56. If you are working with JSON what data structure should you use?

57. If you need keys that can hold any data type what data structure should you use?

58. If you need to remove duplicates, what data structure should you use?

59. If you need to easily access and write values what data structure should you use?

60. If you need better performance, easy iteration, size computation and only key/value pairs, what data structure should you use?

61. If you need a this keyword to access properties, which data structure should you use?

62. Are string methods case sensitive?

63. Strings have methods even though they are primitives. What is boxing in Javascript?

64. What do the index methods return if no match is found?

65. Create a variable that holds a string of letters or words at least 10 characters in length (spaces included). Find the index of a letter, find the last index of a letter, find the index of a word (notice the index returned).

66. What does the slice method do?

67. Slice part of the created string.

68. Slice the string using the index of method.

69. Slice the string using the last index of method.

70. Slice the string using a negative number as the second value.

71. An airplane has middle seats that contain the letter B or E. Create a function that takes in a single seat number and slices the letter to check if the seat is a middle seat or not and console logs an appropriate message. Use the following seats. 11B, 23C, 3E.

72. Change the following string to only have an uppercase first letter with all the rest lower case. lOwkEy. Use the to lower case, to uppercase and slice methods.

73. Confirm two emails are equal when entered with incorrect casing and additional spaces. Email 1: "hello@gmail.com". Email 2: "     Hello@gmAil.Com". Use the to lower case and trim methods.

74. Convert a price in euros (288,97£) to USD. Use replace to change the comma to a period and the pound sign to a dollar sign.

74. Use the replace method with a regex to change door to gate in the following string. "All passengers come to boarding gate 23. Boarding gate 23".

75. Check to see if the string from #74 includes, starts with or ends with words of your choice.

76. Split the string from #74 on all spaces.

77. Create a first name and last name variable and join them with a space, the last name capitalized and title of "Mr." prepending it.

78. Create a function that takes in a full name that is all lowercase and changes the first letter of each name to a capital. Make it robust by lowercasing the whole name first.

79. Create a string variable of any type. Prepend 5 string characters to the beginning and log it. Append 5 string characters to the end of it and log it.

80. Create a function that takes in a 16 digit number. Convert it to a string, slice the last four off and store it in a variable, then prepend that variable with a dot for the remaining length of the just sliced string.

81. Call the repeat method on a variable.








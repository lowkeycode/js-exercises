1. Name all Javascript data types.

2. Explain the difference between reference types and primitives. Additionally use Object.assign to create a shallow copy of an object. Then alter an array (which is an object) inside of the copied. Log both objects.

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

49. If you have a simple list what data structure should you use? Array or Set.

50. If you have key/value pairs which structure types should you use? Map.

51. If you need an ordered list that may contain duplicates, what data structure should you use? Arrays.

52. If you have unique values what data structure should you use? Sets.

53. What data structure should you use if you need to include functions? Objects.

54. If you need to manipulate data, what data structure should you use? Arrays.

55. If you require high-performance (up to 10x faster than arrays for lookup/delete) which data structure should you use? Sets.

56. If you are working with JSON what data structure should you use? Objects. Easily converts to Arrays.

57. If you need keys that can hold any data type what data structure should you use? Maps.

58. If you need to remove duplicates, what data structure should you use? Sets.

59. If you need to easily access and write values what data structure should you use?

60. If you need better performance, easy iteration, size computation and only key/value pairs, what data structure should you use? Maps.

61. If you need a this keyword to access properties, which data structure should you use? Object.

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

82.  What is a first class function?

83. What is a higher order function?

84. What is abstraction?

85. Write a higher order greet function that takes in a greeting and returns a function that takes in a name. Call it using the inner function. Call it using the outer function.

86. Explain the call method.

87. Create an airline object that includes the name of the airline, the airline code, an empty bookings array and a book method that takes in a name and flight number that pushes the flight to the bookings array.

88. Create a different second airline object with all the same properties as the first, EXCLUDING the book method.

89. Create a global book function by storing the first objects book method in a variable.

90. Use the call method on the variable to book a flight on the second object.

91. Explain the apply method.

92. Create a different third airline object with the same properties as the second. Use the apply method to book a flight on the third object.

93. Use the call method with the spread operator to book a flight on the third object. Which one is used more in modern js, call or apply? 

94. How does the bind method work? 

95. Create a variable that holds the value of the book.bind method being called on the second object. Use the variable (now a function) to book a flight on the second object.

96. Use a code editor. Create an airline object holding the amount of planes the airline has. Add a buyPlane method that increases the planes by 1. Create a simple buy button. Add an event listener for a click with the airline.buyPlane method. Explain what is happening with the this keyword and what is happening with the airline.buyPlane method. To fix this which method should be used? Call, Bind or Apply? Why? Fix the event listener.

97. What is encapsulation?

98. What is an IIFE?

99. Write a plain code block with let,const and var with numbers assigned to them. Access the variables from a console log outside the block. Why is the result what it is?

100. What is a closure?

101. Write a closure. console.dir the function in Chrome and view the variables inside the Scopes tab -> Closure tab.

102. What is the difference between slice and splice? How are they each used?

103. Create an array with the length of ten holding randomly generated numbers between 1 and 50. Use slice on it. Console log the array. Use splice on it. Console log the array. 

104. How is the reverse method used? Use the reverse method on the array. Console log the array.

105. How is the concat method used? Use the concat method on 2 new arrays with random numbers between 1 and 50 and the length of 5 for each.

106. How does the join method work? Use the join method on the concatted array from #105 to separate each number by a dash.

107. How does the forEach method work on an array?

108. Create an array of bank withdraws/deposits called movements, between -1000 and 2000 with the length of 10. Use a for of loop to console.log based on a conditional stating if it was a withdrawal or deposit and number each movement by index. Show the numbers only in positive amounts for both deposits AND withdrawals.

109. Do the same as #108 with the forEach method.

110. What is the difference between forEach and the for of loop? Use the 2 differences in the for of loop.

111. How does the forEach method work on maps and sets?

112. How do you set a throw away variable in a function?

113. What is the difference between textContent and innerHTML?

114. Why should you create a copy of an argument passed to a function when altering it within the function?

115. Explain the map method.

116. Explain the filter method.

117. Explain the reduce method.

118. Create a new movements array of random numbers between -500 and 500 with the length of 10. Create a conversion rate variable. Use the map method to get the converted currency array. Console lof the converted array. Console log the original array.

119. What is the main difference between map and forEach?

120. Create an accounts array holding 3 user objects. Create a function that creates a username being the first letter of each first, middle and last name lowercased.(Hint - use forEach and map)

121. Use the filter method to get all deposits from the original array in #118. Get all the withdrawals.

122. What is the big advantage of using these built in methods over the for of loop?

123. Use the reduce method to get the total of all the movements from the original array in #118.

124. Create an array of random numbers between -500 and 100 with the length of 15. Use filter, map and reduce to get the total of all the deposits converted to a different currency with a conversion rate of 1.3.

125. When chaining the above methods, access the array param to look at the data to ensure only deposits (positive numbers) are getting returned.

126. What is a downfall to chaining methods?

127. Explain the find method. Use it on a random array.

128. How can you reset multiple variables?

129. Use optional chaining with the nullish coalescing operator.

130. Explain the findIndex method.

131. What is a major use case of splice?

132. What is the difference between findIndex and indexOf?

133. Explain some and every.

134. Explain flat and flatMap.

135. Create an array with a nesting 1 level deep. Use the flat method on it. Create an array with a nesting 3 levels deep. Use the flat method on it.

136. Create 4 different account objects with different movements in them. Store them all in an array. The bank wants to get the overall balance of all accounts. Use the map, flat and reduce method, chaining them.

137. Do the same as #136 with flatMap.

138. Explain the sort method.

139. Create an array of random numbers between -1000 and 1000 that has a length of 50. Sort them descending comparing with > and <. Sort them ascending using subtraction.

140. Use a code editor. Create 10 paragraphs centered on the page in a column. Use Array.from to store them in an array.

141. Explain why we usually want to convert different data structures to Arrays when working with them.

142. Explain each method after naming. Which array methods insert data? Delete data? What is to be remembered when using reverse, sort or fill? Which methods should be used to create a new array? Which methods should be used to find the index? Which method to use to get an array element based on a conditional? Which methods to use to see if an array hold certain elements? Which method to build a string from an array? Which method to use to transform all the values to a single one? Which methods to loop over an array?

143. Explain a floating point number.

144. How are numbers stored in JS? What does this have to do with fractions in JS?

145. How do you easily convert a string to a number?

146. Explain parseInt and parseFloat. Use them on a decimal number.

147. Explain isNaN, isFinite and isInteger. Which is the best to check if a value is a real number?

148. What are the 2 ways to get the square root of a number? How do you get the cubic root of a number?

159. Explain the max and min methods.

160. Get the area of a circle that has a radius of 10px;

161. Explain the trunc, round, ceil, toFixed and floor methods. Use them. What is the difference between trunc and floor?

162. How do you check if a value is odd or even?

163. Use a code editor. Create 10 paragraphs centered on the page in a column. Spread the nodelist into an array and use the modulus to style each even number paragraphs background color to a different color

164. Explain BigInt and the syntax to use it.

165. What is the Unix Epoch?

166. Name the 4 ways to create dates with the Date object. What is a good practice when creating dates?

167. Create a variable called future that stores a new date with the following arguments. 2037, 10, 19, 15, 23. Call the getFullYear,getFullMonth, getDate, getDay, getHours, getMinutes, getSeconds, toISOString and getTime method on it. Call the Date.now method. 

168. What are the setting methods for dates?

167. Use padStart and a template literal to prepend any 1 digit day with a 0.

168. Use a code editor. Create 10 divs that will be user cards with a name and photo. Make them look half decent. Hit the API at https://randomuser.me/photos. Loop over the node list as well as the returned JSON at the same time to set each photo and name.

169. Create a function that calculates the number of days passed between 2 dates. Use the abs method to return a positive number.

170. Explain the IntlTimeFormat API.

171. Use a code editor. Create a centered div on the screen. Use the IntlDateTimeFormat to display the current day, month, date, year and time. Add ordinals to the day.

172. Explain setTimeout and setInterval. Use them both. Clear them both.

173. What is the DOM?

174. What is an HTML Collection and how do you select one?

175. What is the difference between textContent and innerHTML?

176. Use a code editor. Create a div DOM element. Change the textContent. Change the innerHTML. Prepend it to a container div. Append it to a container div. Use the before and after methods to insert the div in the container. use the cloneNode method on the div when calling the append. Use the remove method to remove the div from the DOM.

177. Explain the getComputedStyle method. Use it on a random webpage element.

178. Explain the setProperty method. Use a code editor. Create a single div. Use the setProperty method on it.

179. Using the div from #178 add a two word data attribute on the HTML and log it in the console.

180. Explain scrollTo and scrollInto View. Use a code editor. Create 3 section 1000px high. Use the methods on the second and third sections.

181. Using the following snippet explain the 3 stages of event propagation and path when clicking on the link element.

```html
<html>
  <body>
    <section>
      <p>
        <a>link</a>
      </p>
    </section>
  </body>
</html>
```

Use the following functions and add an event listener to the section, paragraph and link for a click running the randomColor function to observe more visually what happens.


```js
const randomInt = (min, max) => {
  return Math.floor(Math.random() * (max - min + 1) + min);
};
const randomColor = () =>
  `rgb(${randomInt(0, 255)},${randomInt(0, 255)},${randomInt(0, 255)})`;
```

182. How do you stop event propagation? How do you listen to capturing instead of bubbling?

183. Explain target and currentTarget.

184. What is event delegation? What are the 2 steps to implementing event delegation?

185. Use a code editor. Create a header with 3 links to the corresponding sections. Create 3 section 1000px high. Add basic styles as needed. Use event delegation to smooth scroll (using scrollTo and scrollIntoView) to each section make it robust where if a fourth link and section are added, they already work.

186. Explain the closest method.

187. Use a code editor. Create a tabbed component. Ensure the tab has is labeled with a name and number. Wrap both in a button. Wrap the number in a span inside the button. Make use of the closest method. Use the following mockup to build the HTML and styles.

![Tabbed Component](https://github.com/lowkeycode/js-exercises/blob/master/tabbed-component.png)

185. Explain the bind method. Use a code editor. Create a header nav with 5 links. Style as required. Create an event handler function that changes the opacity and border-bottom on mouseover/mouseout. (Hint use the bind method.)

186. What is the downside of using the scroll event listener? What should be used in its place. Explain it.

187. Use a code editor. Create a sticky nav using the API alluded to in #186.

188. Use a code editor. Create a reveal elements on scroll using the API from #186.

186. Explain lazy loading.

187. Get some images from unsplash. Create a lazy load on scroll. Make sure to apply a css filter to blur the smaller images. (Hint utilize the data attribute in the html)

188. Explain lifecycle DOM events.

189. Explain the difference between async, defer and regular placement of the script tag at the end of the body.

190. Explain OOP. 

191. Explain the 4 main principles of OOP.

192. Explain prototypal inheritance/ prototype chain. Explain the prototype property. What are 3 ways to implement it?

193. Explain constructor functions. What 4 things happen when calling the constructor? Use a constructor function to create a person class. Create 3 people with it.

194. Add a method to the person class from #192.

195. Explain ES6 Classes. Explain properties/methods defined inside the constructor. Explain ones defined outside the constructor.

196. Explain setters and getters. Can a setter and getter be named the same? What is the requirement of setters?

197. Explain static methods. Explain instance methods.

198. What is important to remember about arrow functions when working with OOP?

199. If a method or property is not found in the prototype chain, what is returned?

200. Explain Object.create.

201. How do you create inheritance with constructor functions? What all needs to be inherited?

202. Using a constructor function, create a person class with a student class that inherits from the person. Use an inherited method from person. Define and use a method for student.

203. How does inheritance work in ES6 classes? Rewrite the constructor function in #202 to be a class.

204. How is polymorphism used in classes? Write a polymorphed method in the class from #203. Compare the students method to the person method of the same name.

205. How does inheritance work with Object.create? Write a PersonProto function constructor with 2 methods. Create an extended class with it using Object.create called StudentProto. Use the inherited methods.

206. What are the 4 steps to project planning? Describe each of them in detail.

207. What needs to be kept in mind when we retrieve an object from local storage?

208. Explain asynchronous vs synchronous.

209. Explain AJAX and how it works.

210. Explain what an API is.

211. Use a whiteboard or a piece of paper. Explain how the web works in a diagram. Additionally explain HTTP requests/responses.

212. Explain callback hell.

213. Explain promises, the .then method, the .catch method and the .finally method.

214. Explain why and when we have to manually throw errors with fetch and how.

215. If there are 2 AJAX calls chained what should be done to handle both errors?

216. Use a code editor. Use promises with .then and .catch to make an AJAX call to https://restcountries.eu/ and implement error handling. Display some information about a country and a neighboring country.

217. Use a whiteboard. Explain how the following code is run asynchronously in the browser. Hint there are 5 main parts.

```js
el = document.querySelector("img");
el.src = "dog.jpg";
el.addEventListener("load", () => {
  el.classList.add("fadeIn");
});

fetch("https://someurl.com/api").then((response) => console.log(response));
```

218. Explain how to manually create a promise and the use cases for creating them. (Promisifying).

219. Use a code editor. Promisify the web geolocation api. Reverse geocode it using a reverse geocode api to get the users current location. Using the reverse geocode use the https://restcountries.eu/ api to display the users country.

220. Explain async/await.

221. Explain error handling methodwith async/await. 

222. Explain running promises in parallel and the 4 associated methods.

223. Explain the build process (Bundling, compressing, minifying, compiling, transpiling, tree shaking and polyfilling).

224. Explain ES6 Modules vs a regular script and how modules are imported.

225. What are the 2 types of exports?

226. How were modules implemented prior to ES6 modules.

227. Explain CommonJS modules and why we need them and their relation to npm.

228. Use a code editor. Use lodash to deep clone an object.

229. Explain hot module replacement in parcel and how to write it.

230. Explain the benefit of a library like core-js in relation to parcel/babel.

231. What does the npm package regenerator runtime do?

232. What makes code readable? (5 things)

232. What are 4 general rules of coding JS?

232. What are 5 general rules for functions?

233. What are 4 general rules for OOP in JS?

234. What are 5 ways to avoid nested code?

235. What are 3 general rules of using asynchronous code?

236. Explain imperative vs declarative.

237. Explain functional programming, side effects and pure functions.

238. Explain reformatting the data from an api request that would have underscores that are not desired.

239. Explain importing an icons image file with parcel than holds multiple svg icons and how to use it when rendering som markup.

240. Explain the hashchange and load event and using them together.

241. Explain the 3 main paradigms of a good architecture.

242. Explain the 5 main components of an architecture.

243. Explain the MVC architecture and separate the 5 main components of an architecture into the 3 sections.

242. Explain the 2 special modules that are exceptions to th rest of the architecture and what they hold.

243. Explain the publisher/subscriber pattern and what problem it solves.

244. When creating/implementing a new feature what part should be working first.

245. Use a code editor. Implement a search bar to filter data from an api. Display results that match.

256. Implement pagination for the results from #245.

257. Explain creating a virtual DOM and why to do so.

258. Explain state and how to store it.

# Reactjs Program

### Chapter 1

  ##### Imperitive vs Declaritive.  
   - ##### Imperitive (How)
   ```javascript
   var numbers = [4,2,3,6]
   var total = 0
   for (var i = 0; i < numbers.length; i++) {
     total += numbers[i]
   }
   ```
   - ##### Declaritive (What)
   ```javascript
   var numbers = [4,2,3,6]
   numbers.reduce((previous,current) => {
   return previous + current
   })
   ```
   ##### Pros:
    - Reduce Side Effects
    - Minimize Mutability
    - More readable code
    - Less Bugs

  ##### Composition

  - Think of pages in terms of components.
  - Break it down into components.  
  - Think **functional**

  ##### Explicit Mutation

  - explicity set things. (i.e. `setState`)

  ##### What is React Router?
 - Map different components to different URL's

  ##### What is Webpack?
 - Bundles all of our code into one file.
 - you can run transformations on the code. (i.e from ie6 to ie5)

 ##### What is Babel?
 - Transforms code - JSX to JS.
 - Has a list of presets. (React being one of them)

 ##### What is Axios?
 - Making HTTP request to third parties.

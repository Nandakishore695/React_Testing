# React_Testing

**1. What is testing?**
- Software testing is the process of finding errors in a software product before it is launched, validating the functioning and features of the software

**2. What type of testing?**

There are 2 types of testing:
- Manual Testing
-	Automatic Testing

**3. What type of testing is done by developers?**
-	Unit testing          // single component
-	Integrated testing    //two-component
-	E-2-E testing         // overall project

**4. What Types of React Testing Tools?**
-	Jest Framework
-	React testing library

**5. Create a basic test function?**
```
Create a sum.js file:
export default function sum(a, b) {
  return a + b;
}

Another create a sum.test.js file:
import sum from ".sum.jsx";

test("adds  numberers", () =>{
    expect(sum(10, 20)).toBe(30);
})

Add the following section to your package.json:
"scripts": {
    "test": "jest"
  }
```

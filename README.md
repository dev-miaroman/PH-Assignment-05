# 🌟 Welcome To (সহজ সরল সিম্পল) Assignment - 5

# **📅 Deadline For 60 marks:** 9th March, 2026 (11:59 pm ⏱️)  
#  📅 No Deadline For 50 marks  
# **📅 Deadline For 30 marks:** Any time after 9th March.

---

# Assignment-05: GitHub Issues Tracker


### **API Endpoints:**
###  **All Issues:** 
  - https://phi-lab-server.vercel.app/api/v1/lab/issues 


###  **Single Issue:**
   - https://phi-lab-server.vercel.app/api/v1/lab/issue/{id}

   - Example: https://phi-lab-server.vercel.app/api/v1/lab/issue/33


###  **Search Issue:** https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q={searchText}

   - Example:  https://phi-lab-server.vercel.app/api/v1/lab/issues/search?q=notifications


---

## 📝 Main Requirements

## 🎨 Design Part

## Login Page
- Create a login page containing a logo, title, and sub-title
- Below that, there will be 2 inputs, a sign-in button, and a demo credential to sign in. Follow the Figma for this page 
- Styled as per Figma

## Main Page: 

### Navbar: 

- Navbar with website logo/name on the left
- Search input and button on the right

### Tab Section like Figma: 

- 3 tab ( All, Open, Closed) at the top of this section.(**All**, **Open**, **Closed**)

- Below the tab, there will be an icon, the issue count, some text on the left, and an open and closed marker on the right

- Responsiveness: The website should be responsive for mobile devices. It is totally up to you. 


--- 


## ⚙️ Functionalities
- In login page, there will be default admin credentials (username, password). You need to sign in using these credentials.

- Load all issues and display as per Figma

- On clicking on an open or closed tab, it will load the issues data of the related tab and show it in a display-like card in a 4-column layout like Figma. By default, it will show all data 

- Each card shows:
  - Title
  - Description
  - Status 
  - Author
  - Priority
  - Label
  - CreatedAt
- Clicking on an issue  card will open a modal and show all the information about that Issue. 

### 🚀 Challenges


- Show the card Top border based on their category(open, closed), open card will have Green Boder, closed card will have a purple border on top. 

- Loading spinner on data load

- Show active button on changing category names

- Implement Search Functionality and 8 meaningful github commit.  

- Create a readme file and answer this question on your own. Don’t copy-paste from Google or any AI chatbot. 


1️⃣ What is the difference between var, let, and const?
- Answer: 
- Var: var is used to declare a variable that is function-scoped and can be redeclared and reassigned.Example-
-	    var x = 1;
-	    var x = 2;   // Redeclaration allowed
-	    x = 3;       // Reassignment allowed
-	    console.log(x); // 3

- let: let is used to declare a block-scoped variable that can be reassigned but cannot be redeclared in the same scope.-Example-
-	  let y = 1;
-	  y = 2; // Reassignment allowed
-	  console.log(y); // 2
	
- const:const is used to declare a block-scoped variable whose value cannot be reassigned after initialization.Example-
-	  const z = 1;
-	  // z = 2; // Error (cannot reassign)
-	  console.log(z); // 1


2️⃣ What is the spread operator (...)?
- Answer:
- The Spread Operator (...) is used to expand or unpack elements of an array, object, or iterable into individual elements.Example-
-	  const numbers = [1, 2, 3];
-	  const newNumbers = [...numbers, 4, 5];
-	  console.log(newNumbers); // [1, 2, 3, 4, 5]


3️⃣ What is the difference between map(), filter(), and forEach()?
- Answer:
- map(): map() creates a new array by applying a function to every element in the original array. It "maps" each old value to a new value.Example-
-	  const numbers = [1, 2, 3, 4];
-	  const doubled = numbers.map(num => num * 2);
-	  console.log(doubled); // [2, 4, 6, 8]

- filter(): filter() creates a new array containing only the elements that pass a specific "test" (a condition that returns true).Example-
	  const numbers = [1, 2, 3, 4, 5];
	  const evenNumbers = numbers.filter(num => num % 2 === 0);
	  console.log(evenNumbers);// [2, 4]

-forEach(): forEach() executes a provided function once for each array element. It is used when we want to do something but we don't need to create a new array. Example-
-	  const numbers = [1, 2, 3];
-	  numbers.forEach(num => {
-  	console.log(num * 2); 
-	}); //2 //4 //6

4️⃣ What is an arrow function?
- Answer:
- An Arrow Function is a shorter and cleaner way to write functions in JavaScript. It was introduced in ES6 (ECMAScript 2015) and we uses the => (arrow) syntax. Example-
-	  function add(a, b) {
- 	  return a + b;
-	  }
- Arrow Function:
-	  const add = (a, b) => {
-  	return a + b;
-	};
-	  console.log(add(3, 4)); // 7


5️⃣ What are template literals?
- Answer: 
- Template literals are a modern way to work with strings in JavaScript, introduced in ES6. They offer more flexibility than traditional strings wrapped in single (' ') or double (" ") quotes and create a template literal, we use backticks (`) instead of quotes.They allow embedding variables and expressions inside a string using ${}. Example-
-	const name = "Roman";
-	const message = `Hello ${name}`;
-	console.log(message);// Hello Roman



---

## 🛠️ Technology Stack

- **HTML**
- **CSS** (Vanilla/Tailwind/DaisyUI)
- **JavaScript** (Vanilla)

---

## 🔑 Demo Credentials

```text
Username: admin
Password: admin123
```


---

### Optional: 
 - No need to show status: Open, Closed styles On modals. 
 - No Need to show icon on labels 
 - No need to apply styles on Priority 
--- 


## 📤 What to submit

- **GitHub Repository Link:**
- **Live Site Link:**

---



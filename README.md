# Inception_Assignment
//It contains the QnAs//
1. What is Emmet?
>>Answer: Emmet is a tool that helps you write HTML and JSX code faster by using shortcuts. It’s built into many code editors like VS Code, 
       and it expands simple abbreviations into full code snippets.
  EXAMPLE:<div className="container">
  <h1>Hello</h1>
  </div>
        Emmet will turn this above JSX code into a shortcut.
  SHORTCUT(Emmet code):div.container>h1{Hello}
  When you write the above emmet code into code editor it will automatically convert it into the original JSX code. 
  Some code editors like VSCode supports and have built-in emmets.

2. Difference between Library and Framework.  
>>Answer:
   Framework:
   Think of a framework as a pre-built house. It provides the structure, plumbing, and wiring. You just move in and furnish it according to 
   your needs. The framework calls your code at specific points, guiding the flow of your application.
   Library:
   A library is like a toolbox. You pick and choose tools to help you build or fix things as you go. You call the functions or methods from 
   the library when you need them.

3. What is CND? How do we use it?
>>Answer: A CDN (Content Delivery Network) is a network of servers around the world that deliver files (like images, CSS, JavaScript) to 
          users faster by using the server closest to them.
>>You use a CDN by including a link to a hosted file in your HTML.
  As in for react:- You can include React and ReactDOM in a plain HTML file using CDN links:
                    <!-- React (development version) -->
                    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>

                    <!-- ReactDOM (development version) -->
                    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

4. Why React is known as React?
>>Answer: React is called "React" because it's designed to "react" to changes in data and update the user interface automatically.

5. What is Crossorigin in script tag?
>>Answer: This enables a better error handling experience in React 16 and later.

6. What is diference between React and ReactDOM.
>>Answer: 


7. What is difference between react.development.js and react.production.js files via CDN?
